#### 0.2.5 (2022-03-29):
* Added "_OB_APP_TITLE" property

#### 0.2.4 (2021-05-16):
* Fixes #3: OBApps crashes on start with wxPython v4.1.1

#### 0.2.3 (2021-04-15):
* Fixes #2: OBApps fails to launch if there is no application tag in the applications-section of rc.xml

#### 0.2.2 (2020-02-24)
* First try on fixing GUI
* Fix GUI and AboutDialog, bump version to 0.2.2

#### 0.2.1 (2020-02-14):
* Fix python shebang (duh!)

#### 0.2.0 (2020-02-13):
* Code converted to Python3 (2to3).
* Fixed wxPyDeprecationWarnings

#### 0.1.7 (2010-07-09):
* Maximized setting of both in GUI now properly translates to "yes" in XML.
* Fixed locale-dependent error checking when locating config file.

#### 0.1.6 (2010-06-03):
* Crosshair cursor for find; status bar removed

#### 0.1.5 (2010-05-22):
* No longer crashes if root window is clicked on during find.
* Xlib-dependent code moved to separate module.

#### 0.1.4 (2010-05-15):
* Determine correct config file if not using the default.
* Blank name/class/role/type values are loaded properly.
* Added proper installation script and removed '.py' extension.

#### 0.1.3 (2010-05-15):
* Changed to python-xlib for window picker. This removes dependency on python-wnck and allows picking to work across desktops.
* Added statusbar to indicate picking status because python-xlib doesn't seem to allow changing the cursor in a pointer grab.

#### 0.1.2 (2010-05-13:
* Automatically reconfigure Openbox when changes applied.
* Removed internal constraint on radio box titles.

#### 0.1.1 (2010-05-12):
* Added icons to buttons.

#### 0.1.0 (2010-05-12):
* Initial release
