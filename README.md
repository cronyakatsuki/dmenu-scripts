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


