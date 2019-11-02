# Pit
Pit is a profile manager for git, it allows you to quickly switch between various git accounts, setting your username, email and ssh key as needed. Just slap the application somewhere in your PATH (like `/usr/share/bin` or something) and you're good to go. I wrote this because I was sick of having to having to faff about when I wanted to work on my personal projects when my defaults were all set for work.  

```
Usage: pit [PROFILE] [OPTION]
Switch between git profiles easily.

  -h display this help text and exit

When executed without specifying a profile pit will display all profiles.
A profile can be specified either by its numeric id or its name.

The file ~/.pit contains your pit profiles in CSV format
This CSV file is in the format profile,email,name[,keyfile]
If a keyfile is not specified pit will automatically search for a filename
matching the profile email in ~/.ssh
```
