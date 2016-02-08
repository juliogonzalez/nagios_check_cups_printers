check_cups_printers
===================

A Nagios/Icinga python plugin to check CUPS printer statuses.

Based on the idea of [check\_cups\_printer](https://exchange.nagios.org/directory/Plugins/Operating-Systems/Linux/check_cups_printer/details), but without using lpstats, and
allowing checks for one, several or all printers available at a CUPS server.

The plugin will either return an OK if all selected printers are idle or printing, or a CRITICAL for anything else. 

Requires python2.6+ and [pycups](https://pypi.python.org/pypi/pycups).

Get help with:
```
./check_cups_printers -h
```
