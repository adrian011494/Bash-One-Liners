# Bash-One-Liners
[![asciicast](https://asciinema.org/a/mRIUpAC4zk1W3lPDpyxRNQWDa.png)](https://asciinema.org/a/mRIUpAC4zk1W3lPDpyxRNQWDa)

[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/adrian011494)

`liners` is a power tool to [Mash One-Liners](http://www.bashoneliners.com/) Search from the command-line. It shows the title, URL, command and explication for each result. 

###Usage
####Command line options

```
usage: liners [-h] [-n N] [KEYWORD [KEYWORD ...]]

Bash One-Liners from the command-line.

positional arguments:
  KEYWORD          Query to search in http://www.bashoneliners.com/

optional arguments:
  -h, --help       show this help message and exit
  -n N, --count N  show N results (default 10)
```
####Example
```commandline
liners -n=2 convert a file
```  

### Developer

 Copyright © 2017 Adrian Arencibia Herrera adrian011494@gmail.com