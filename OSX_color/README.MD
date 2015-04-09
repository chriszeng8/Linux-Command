##Adding Colors to your OSX Terminal

How to let Terminal on Mac OS behave show folders and executables and such in different colors?

1. open your .bash_profile (by entering ```open ~/.bash_profile``` in your terminal)
2. add the following two lines at the bottom of your line:

```export CLICOLOR=2;```

```export LSCOLORS=gxfxcxdxbxegedabagacad;```

Note: Be careful, and do not overwrite your original file, we only want to append these two line.

3. save and quit the ```.bash_profile file```, and restart your terminal, then Voila!!!

Source: [StackOverflow](http://apple.stackexchange.com/questions/18239/how-to-let-terminal-on-mac-os-behave-show-folders-and-executables-and-such-in-di)