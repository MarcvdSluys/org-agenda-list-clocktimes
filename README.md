# org-agenda-list-clocktimes #

A command-line tool written in Python to print the clock times for your emacs orgmode agenda items for a
given week.  Most work is done by the [orgparse](https://github.com/karlicoss/orgparse) package by
Karlicoss.

## Example use ##

```text
$ org-agenda-list-clocktimes -h
usage: org-agenda-list-clocktimes [-h] [-w LASTWEEK] [-v] fileName

List orgmode agenda clock times for a given week.

positional arguments:
  fileName              name of the orgmode agenda file to process

optional arguments:
  -h, --help            show this help message and exit
  -w LASTWEEK, --lastweek LASTWEEK
                        print results for LASTWEEK weeks ago: 0-this week,
                        1-last week, 2-two weeks ago, ... (default: 0)
  -v, --verbosity       increase output verbosity (default: 0)
```

```text
$ org-agenda-list-clocktimes Work.org  # List clock times in Work.org for the current week.

$ org-agenda-list-clocktimes Work.org -w 1  # List clock times for last week.
```


## Author and licence ##

* Author: Marc van der Sluys
* Contact: http://marc.vandersluys.nl
* Licence: [GPLv3+](https://www.gnu.org/licenses/gpl.html)


### How to thank me ###

In order of increasing gratitude:
1. Use more open-source software for whatever it is you are doing.
1. Contribute to other open-source-software projects.
1. Create and publish your own open-source software package.

