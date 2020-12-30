# Visual Studio Cheat Sheet for Mac

## Commonly Used Keyboard Shortcuts
### Add cursor to all instances of selected code

Shift + cmd + L

A note here - if you're using the [Loom](https://www.loom.com/) app it overrides this shortcut! You'll have to quit Loom to use it.

### Find instance of selected in current file

cmd + f

### Find instance of selected with Replace in current file

cmd + alt + f

### Find in all files

shift + cmd + f

### Find file by name

cmd + p

### Add cursor to the line above

alt + cmd + up arrow

### Add cursor to the line below

alt + cmd + down arrow

### Copy currently selected line(s) to above

shift + alt + up arrow

### Copy currently selected line(s) to below

shift + alt + down arrow

### Highlight to beginning of line from cursor

Shift + cmd + left arrow

### Highlight to end of line from cursor

Shift + cmd + right arrow

### Move cursor to beginning of previous word

alt + left arrow

### Move cursor to end of next word

alt + right arrow

### Move and select to beginning of previous word

alt + shift + left arrow

### Move and select to end of next word

alt + shift + right arrow

### Move to file top

cmd + up arrow

### Move to file bottom

cmd + down arrow

### Comment code

cmd + /

### Close current tab

cmd + w

### Close all but current tab

alt + cmd + t

### Move to tab right

alt + cmd + right arrow

### Move to tab left

alt + cmd + left arrow

### New tab

shift + cmd + t

### Split editor vertically

cmd + \

### Go to line

ctrl + g

### Toggle the Terminal in the editor

ctrl + `

## Editor Customisation

### Open Settings

cmd + ,

### Choose tab highlight colour (with Material Theme)

shift + cmd + p

...and type 'Material Theme: Set accent color'

Press enter to choose a colour

### Change editor title and/or status bar colour

cmd + ,

...to open Settings. Then type 'workbench color customizations' and under 'Workbench: Color Customizations' click 'Edit in settings.json'

This will create a .vscode folder and inside that a settings.json in the root of your current project. Add the following to the settings.json to amend the title and status bar colours...

`
{
  "workbench.colorCustomizations": {
    "titleBar.activeBackground" : "#49da3b",
    "statusBar.background" : "#49da3b",
  }
}
`

Options are listed on [visualstudiocode.com](https://code.visualstudio.com/api/references/theme-color)

## Diff between two files

In the terminal:

`code --diff filename filename2`

Or in the editor, right click the first file for comparison and choose 'Select for Compare'. Then right click the second file for comparison and choose 'Compare with Selected'.

## Preview a markdown file

Right click the file and choose 'Open Preview'.