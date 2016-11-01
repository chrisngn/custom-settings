# My custom settings for my Mac

## Reduce window resizing animation time
defaults write -g NSWindowResizeTime -float 0.003;killall Dock

## Undo the change above
defaults delete -g NSWindowResizeTime

## Showing toolbar or menu bar in full screen
defaults write -g NSToolbarFullScreenAnimationDuration -float 0;killall Dock

## Undo the change above
defaults delete -g NSToolbarFullScreenAnimationDuration

## Adding blank space to dock
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}';killall Dock

## Show the path in finder
defaults write com.apple.finder _FXShowPosixPathInTitle -bool true; killall Finder

## Resetting Terminal preferences
http://superuser.com/questions/427154/reset-mac-os-x-terminal-to-default

## Make a symbolic link to use "subl" command via Terminal
https://www.sublimetext.com/docs/2/osx_command_line.html

## Move the "x" button to the right and the "volume indicator" to the left
https://vivaldi.net/en-US/forum/all/8783-move-tab-close-button-to-right-side-of-tab

https://vivaldi.net/en-US/forum/modifications/14431-vivaldi-ui-customisations#24433