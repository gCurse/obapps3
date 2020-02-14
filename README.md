# obapps3
#### [OBApps](https://sourceforge.net/projects/obapps) (by Eric Bohlman) 2to3ed, works with Python3, wxPython4

### A graphical editor for Openbox application settings.
    
#### To install:

* sudo python setup.py install, or just put obapps somewhere on your path and make sure it's executable

#### Requires:
* Python3, wxPython4, python-xlib

#### Usage notes:
* OBApps uses ~/.config/openbox/rc.xml (or the config-file Openbox was started with) by default. You can specify another file as an argument, e.g. obapps.py .config/openbox/myrc.xml

* Enter or change the name, class, role, or type settings by clicking in their entries in the listbox.

* Using the Find button to get settings by clicking on a window changes the settings for the CURRENTLY SELECTED
item in the listbox; it does not add a new entry unless nothing is highlighted. You'll usually want to use the
New button to create a new item first.

* Blank entries for name/class/role/type are ignored. If you want any of those fields to be stored as literally
blank attributes (e.g. to match only a window with a blank role), enter "" or '' in the field.

* Changes are written to the rc.xml file only when the apply button is used. Openbox will automatically be
reconfigured when this is done (as of version 0.1.2).
    
#### Bugs/limitations:
* Since this code is very preliminary, make sure to back up your rc.xml file before using obapps3.

#### License:
* See [LICENSE](../blob/master/LICENSE)
