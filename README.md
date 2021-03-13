# Welcome to my dmenu scripts repository

## dmenufilehandler

A very simple script that uses the **find** command to list all the file and diretory's in a given path. After selecting one of the files or directory it will open it in your preferred program using xdg-open.

> example

~~~
dmenufilehandler ~/Videos/Anime
~~~

## dmenulinkhandler

A script that uses case to let you choose from a set of programs to open a link that you want in the desired one. Used in my newsboat config.

Programs used in this script are **mpv**, environmental variable **BROWSER**, copying url using xclip and opening the url using w3m.

> example

~~~
dmenulinkhandler gnu.org
~~~

## dmenupass

A scripts that echoes your input into the terminal. Used mostly when asked for sudo password.

## dmenupowermenu

A dmenu power menu script that I use in any tiling wm. You can only shutdown or reboot, but you can add more options if you want.

## dmenuryzenadj

A dmenu script that uses [ryzenadj](https://github.com/FlyGoat/RyzenAdj) to lower my Ryzen laptop processor speed so that it doesn't go hot. Only good if you have **Ryzen 5 3550H**, any other cpu could die using these settings.

## dmenuscreenshot

A script that uses **maim** to take fullscreen or selected area screenshot or **maim + xdotool** for the active window. It can also copy screenshots to directly using xclip. It saves screenshot's into the '~/Pictures/screenshots' directory.
