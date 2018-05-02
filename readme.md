# Intro stools
This is a folder with dumb scripts that I wrote. Go nuts.

## fclip
watch file and put it into the clipboard
basically it just watches your file for changes and puts its contents into your clipboard assuming you're using xclip
useful for coding competitions probably if you want to use external editors(like vim)
### deps:
- xclip

## loc_term - reopen a new xfce4-terminal window in the same directory as the xfce4-terminal window you have selected can ssh if in an ssh session
xfce4-terminal --disable-server
must be enabled since currently, trying to figure out which shell is in the current window is fairly hard and my time is split. Handles ssh and will ssh using the cmdline arguments that were passed to the shell
### deps:
- xfce4-terminal
- xdotool

More to come probably.
