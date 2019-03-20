---------------------
Name: No Saves with exceptions
Creator: JackOfNone
Category: Utilities
Version: 1.0
---------------------
Deletes all save directories in /var/lib/clover/profiles/0/ during system startup except those listed in 
/etc/nosavemod_exceptions.txt

To enable this mod the first line of /etc/nosavemod_exceptions.txt must be "1" (without quotes), it is
set as disabled by default.

every line after the first must contain a single directory that likely follows the form of CLV-x-xxxxx The
easiest way to find the name of the directory you want is to select the game in hakchi and read the
"Command line (for advanced users only!)" box.

The two entries pre-included in the file are for the built in Final Fantasy 3 and Secret of Mana.

Backing up the games you want to keep through hakchi's save state manager (it deals with regular saves too) just 
in case would be a good idea.
