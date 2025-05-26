# expirify

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat)](https://github.com/RichardLitt/standard-readme)
[![GitHub license](https://img.shields.io/github/license/qubist/mirrorboard-mac.svg)](https://github.com/qubist/mirrorboard-mac/blob/master/LICENSE)

Simply and automatically expire files with cron.

## Install
1. Put the included `expirify` script into `/etc/cron.daily`
2. Change the path for `EXPIRING_DIR` to the directory where you want files to expire.

## Usage
To make a new set of files that expire on a certain date, create a folder inside the expiring directory named the date you want them to expire in YYYY-MM-DD format. Expirify will delete them after this date.

Here's an example expiring directory:
```
expiring_directory
├── 2025-05-28
│   ├── arbitrary_stuff
│   │   └── foo.txt
│   │   └── bar.txt
│   └── baz.png
└── 2025-10-01
    ├── oof.jpg
    └── rab.jpg
```

## Contribute 
Pull requests are accepted.

## License

[MIT License](/LICENSE)
