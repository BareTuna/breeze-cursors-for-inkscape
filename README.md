# Breeze Cursors for Inkscape
Replaces the default `.svg` cursors in Inkscape with `.svg` Breeze (Dark) cursors instead. Custom cursors are intended to match the same style as Breeze.

## Pre-Installation Info
### Background
Inkscape has a specifically named `cursors` folder where the cursors exist.
If you modify the `.svg`s in that folder, it will update the cursors in Inkscape.
Knowing this, if we replace the old cursors folder with our new one (and name it `cursors`),
Inkscape will use the `.svg`s in our own `cursors` folder!

### Installation overview
1. Navigate to where Inkscape looks for a `cursors` folder (see below)
2. If a `cursors` folder already exists, rename it to something else
3. Download the `cursors` folder from the files up above, and extract it into the same folder where the old `cursors` folder was
4. Open Inkscape, switch to another tool and back, and Inkscape will automatically update the cursors like magic :sparkles:

For detailed help, follow the instructions below :)

## Installation
### 1 - Navigate to correct folder
#### Linux
If you would like to use these icons **system-wide**, navigate to:\
`/usr/share/inkscape/icons/hicolor/`\
:information_source: *You should see a few folders, including `cursors`*

Otherwise, for local (**user-specific**) inkscape icons, navigate to:\
`~/.config/inkscape/icons/hicolor/`\
:warning: *If that path does not exist, it's likely because `hicolor` hasn't been created yet!
Simply navigate to `~/.config/inkscape/icons/` and create a folder named `hicolor`, open it, and move to step 3, downloading!*

#### Windows
I'm not sure, but I would assume it's under:\
`C:\Program Files\Inkscape\share\icons\hicolor`\
If you know where the correct path is, please let me know!

### 2 - Rename cursors folder to something else
Renaming the `cursors` folder to something else will cause Inkscape to not use that folder for cursors anymore.\
So, rename `cursors` to `default-cursors`.

:information_source: *If you ever want to switch back to the old cursors, rename `default-cursors` back to `cursors`.*

:warning: *If the cursors folder does not exist, double-check your file location from step 1. If you are sure it is right, skip this step, and move on to downloading.*

### 3 - Download the breeze `cursors` directory
Download the cursors folder here:\
[https://downgit.github.io/#/home?url=https://github.com/BareTuna/breeze-cursors-for-inkscape/tree/main/cursors](https://downgit.github.io/#/home?url=https://github.com/BareTuna/breeze-cursors-for-inkscape/tree/main/cursors)\
Download and/or move the `cursors.zip` to the correct folder from step 1

### 4 - Extract
Extract `cursors.zip` into correct directory from step 1.

:information_source: *Make sure the new folder is named `cursors`, and check to make sure when you open that folder, the first thing you see is all the .svg files for the cursors*

### 5 - Done
Open up Inkscape, switch to a different tool then back (i.e. F2, F1) then you should see your cursors already working!

:warning: *If it isn't showing up, try restarting Inkscape, and if not, it's probably because user-specifc Inkscape cursors are taking precendence over system-wide Inkscape cursors.
On Linux, double check that `~/.config/inkscape/icons/hicolor/cursors/` does not use the default Inkscape cursors.*
