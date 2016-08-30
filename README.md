# My custom settings for my Mac

## Reduce window resizing animation time
defaults write -g NSWindowResizeTime -float 0.003;killall Dock

## Undo the change above
defaults delete -g NSWindowResizeTime

## Showing toolbar or menu bar in full screen
defaults write -g NSToolbarFullScreenAnimationDuration -float 0;killall Dock

## Undo the change above
defaults delete -g NSToolbarFullScreenAnimationDuration

## Make a symbolic link to use "subl" command via Terminal
https://www.sublimetext.com/docs/2/osx_command_line.html

## Vivaldi custom css directory
/Applications/Vivaldi.app/Contents/Versions/$version$/Vivaldi Framework.framework/Resources/vivaldi/

## Move the "x" button to the right and the "volume indicator" to the left
https://vivaldi.net/en-US/forum/all/8783-move-tab-close-button-to-right-side-of-tab

https://vivaldi.net/en-US/forum/modifications/14431-vivaldi-ui-customisations#24433