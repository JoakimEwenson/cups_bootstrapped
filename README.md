# CUPS web interface with Bootstrap CSS
_work by Joakim Ewenson (https://www.ewenson.se) in 2020_

Reworking the CUPS template files for using Bootstrap CSS framework to make a better looking and more responsive view of the CUPS web interface.

### Working, mostly
* Home page
* Admin
* Classes list
* Jobs list
* Printers list

### Working, partly
* Add, modify, remove printers
* Add classes

### Needs work
* Just about everything

## Installation

Tested on Raspbian OS on a Raspberry Pi 3B running as a print server. You should do better than me and backup everything in case of failure. Don't be stupid, don't be like me.

* Place *__doc-root__* and *__templates__* into *__/usr/share/cups__*, overwriting the previous files, at your own risk that is.
* Download Bootstrap 4.5+ CSS and JS file, extract to *__/usr/share/cups/doc-root/__*, creating *__/bootstrap/js__* and *__/bootstrap/css__* subfolders.
* Download jQuery 3.5.1+ and place into *__/usr/share/cups/doc-root/bootstrap/js__* folder
