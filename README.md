![bash_unit CI](https://github.com/pforret/postmark/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/postmark/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/postmark)
![GH stars](https://img.shields.io/github/stars/pforret/postmark)
![GH tag](https://img.shields.io/github/v/tag/pforret/postmark)
![GH License](https://img.shields.io/github/license/pforret/postmark)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

# postmark

Use Postmark API on the command line

## Usage
```
Program: postmark.sh 1.0.0 by peter@forret.com
Updated: Jan  3 17:14:14 2021
Description: Use Postmark API on the command line
Usage: postmark.sh [-f] [-h] [-q] [-v] [-B <bcc>] [-C <cc>] [-F <from>] [-G <tag>] [-K <token>] [-M <stream>] [-S <subject>] [-T <to>] [-l <log_dir>] [-t <tmp_dir>] <action> <input?>
Flags, options and parameters:
-f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
-h|--help        : [flag] show usage [default: off]
-q|--quiet       : [flag] no output [default: off]
-v|--verbose     : [flag] output more [default: off]
-B|--bcc <?>     : [option] bcc: address
-C|--cc <?>      : [option] cc: address
-F|--from <?>    : [option] from: address  [default: <author email>]
-G|--tag <?>     : [option] email tag  [default: test]
-K|--token <?>   : [option] Postmark API server token  [default: POSTMARK_API_TEST]
-M|--stream <?>  : [option] Postmark stream  [default: outbound]
-S|--subject <?> : [option] email subject  [default: Mail from <user>@<host> - <date>]
-T|--to <?>      : [option] to: address  [default: example@example.com]
-l|--log_dir <?> : [option] folder for log files   [default: ~/log/postmark]
-t|--tmp_dir <?> : [option] folder for temp files  [default: .tmp]
<action>         : [parameter] action to perform: check/html/text/md
<input>          : [parameter] input text or html (optional)
```

## Installation

with [basher](https://github.com/basherpm/basher)

```bash
basher install pforret/postmark
```

or with `git`

```bash
git clone https://github.com/pforret/postmark.git
cd postmark
```

## Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2021 Peter Forret
