## CloseFolder Sublime Text plugin

A simple Sublime Text plugin to close all open files of current directory or all open files inside some directory. Supports Sublime Text 2 and 3.


### Motivation

1. When doing web development project, the tab count easily shoots up to 30+ in no time. By this time, figuring each tab starts becoming difficult as only few characters of the filename can be seen. With this I can quickly close an *old* folder (which I may not need now) and generate some room.
2. I keep all my college semester lab work in a single project. Whenever I need to make some room, I close a past 'lab' folder.
3. When I take part in a coding contest/marathon, I create a folder for it and then keep all related files in there. By the end of the contest, I easily have 10+ tabs opened for it. This plugin helps me remove them all at once.


### Installing

Search for `CloseFolder` and install it via [Package Control](https://packagecontrol.io).

OR

[Download this repo](https://github.com/aviaryan/CloseFolder/archive/master.zip), extract it and then place *CloseFolder* folder in Packages directory of ST.


### Using

There are 2 commands in this plugin.

1. `close_folder` - Closes all files which are in the same directory as the file opened in the active tab. This can be activated via right clicking in the *Sublime Text editing area* and selecting 'Close Folder' option.

2. `close_folder_dirs `- Closes all files which are inside the selected directory, recursively. This can be activated from the **sidebar** by right clicking on the folder and selecting 'Close Folder' option.

