# Reduce window resizing animation time
defaults write -g NSWindowResizeTime -float 0.003;killall Dock

# Undo the change above
defaults delete -g NSWindowResizeTime

# Make a symbolic link to use "subl" command via Terminal
sudo ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl

# Vivaldi custom css directory
/Applications/Vivaldi.app/Contents/Versions/$version$/Vivaldi Framework.framework/Resources/vivaldi/

# Move the "x" button to the right and the "volume indicator" to the left
https://vivaldi.net/en-US/forum/all/8783-move-tab-close-button-to-right-side-of-tab
https://vivaldi.net/en-US/forum/modifications/14431-vivaldi-ui-customisations#24433