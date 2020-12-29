# dmenu (Run Prompt)
My build of dmenu. Fork from tools.suckless.org/dmenu + applied patches

Patches Applied:
1. highlight: To highlight the entered characters in the selection menu
2. lineheight: To adjust the height of dmenu prompt
3. Mouse support: To scroll and select using mouse

Dependencies:
1. libxft-bgra-git(to support color emoji)
2. Fonts: nerd-fonts-mononoki, ttf-hack, ttf-joypixels

To Install:
1. git clone https://github.com/BadrikeshPrusty/dmenu.git
2. cd dmenu
3. make
4. sudo make clean install
