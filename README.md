archlinux-hello
=============

F.A.Q: 


Q: I do not have a logo icon, where is it?

A: Copy it from data/img/archlinux.png into /usr/share/icons/hicolor/64x64/apps/archlinux.png

Q: I get a python error about COENAME and RELEASE etc when launching it, how do I fix this?

A: Edit the /etc/lsb-release file with a text editor (vim, nano, emacs etc) and add at the very bottom the following line:
   
   DISTRIB_CODENAME="Arch"
   
   The exact name is not relevant, however it must contain something, and Arch is an appropriate value on Arch Linux.




WIP: English language file completely done, German one partially, others will not be altered.

A tool providing access to documentation and support for new Arch Linux users.

## What is Arch Linux Hello?

Archlinux-hello is widely inspired by [manjaro-hello](https://github.com/manjaro/manjaro-hello).
Currently, archlinux-hello has all the major features of manjaro-hello, but with limited translations.
- Interface is translated using gettext and po files (po/). Only german and english files will be adapted for archlinux-hello!
- Pages are translated using differents files (data/pages).

## What goals ?

The goal of the project is to build a powerful user interface that allows the user to discover his favorite distribution :).

## Technologies

Archlinux-hello is build with Python, Gtk3 and Glade.

## TODO

- Make more translations to distribute it in all the world.

## Links
These point to files regarding the original base of this fork, manjaro-hello.
- [Discussion from Manjaro's forum](https://forum.manjaro.org/t/start-work-on-a-new-welcome-screen-for-manjaro/13685)
- [Translation project for Manjaro-Hello](https://www.transifex.com/manjarolinux/manjaro-hello)

Let's make a wonderful software !
