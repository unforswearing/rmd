[![shellcheck](https://github.com/unforswearing/rmd/actions/workflows/shellcheck.yml/badge.svg)](https://github.com/unforswearing/rmd/actions/workflows/shellcheck.yml)

<br>

`rmd`: quick reminders in terminal

`rmd` was originally written by [ttscoff](https://gist.github.com/ttscoff/cded212ec4dd457186ca). This version has been updated to remove LaunchBar integration, add default OSX reminders from [the coddingtonbear fork](https://gist.github.com/coddingtonbear/8cb622e207f6fcf4d22959fecd5d0c44), and pass shellcheck.

To use, download the repo and add it somewhere in your `$PATH`. Usage instructions can be found in the `rmd.bash` script. Here are a couple examples:

```
$ rmd turn off the stove in 20m
=> I'll remind you: "turn off the stove" in 20 minutes

$ rmd leave for dinner in 2h
=> I'll remind you: "leave for dinner" in 2 hours
```

