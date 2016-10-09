# OSXey

Repo is being maintained regally again.

A script for OS X to display system information.

!['Screenshot'](https://raw.github.com/Gary00/OSXey/master/screenshot_normal.png)
!['Screenshot'](https://raw.github.com/Gary00/OSXey/master/screenshot_color.png)

## Auto Install / Uninstall
Use install.sh to both install and uninstall.

## Options
	-c,  --color
		Color Logo

	-red
		Red Text

	-green
		Green Text

	-yellow
		Yellow Text

	-blue
		Blue Text

	-purple
		Purple Text

	-grey
		Grey Text

## To-Do List

### Priority
* Change name as OS X naming no longer is relevant
* Add support for latest versions of OS


### Bug Fixes / Optimization
* Look into $terminalText bug. Maybe find a better way of displaying colors then current method
* Code cleanup
* Update Screenshots
* Better way of changing text color (use ""-text blue"" or "-text red" rather then "-red" or "-blue")
* Test Units (For growing information such as hardware models and OSX versions)
* Add manual install instructions in manual for those who don't want to use installer
* Add color to disk info. Display Green /Yellow / Red for amount of space left. (Option to turn off)

### Features
* Look into being able to install via package manager (homebrew / macports)
* Resolution information
* Easy way to change info being displayed (maybe a config file ?)
