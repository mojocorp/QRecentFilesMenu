## Description

The QRecentFilesMenu class provides a recent files menu widget for use in menu bars, context menus, and other popup menus. 

* Use QRecentFilesMenu::addRecentFile() to insert a recent file into the menu.
* QRecentFilesMenu provides the signal recentFileTriggered to notifed whenever a recent file has been triggered().
* You can save and restore the recent files entries from a QByteArray using saveState() and restoreState() respectively.


<img src="https://raw.github.com/mojocorp/QRecentFilesMenu/master/screen-capture.png" >

## Dependency
Qt 4.x.

## License

LGPL
