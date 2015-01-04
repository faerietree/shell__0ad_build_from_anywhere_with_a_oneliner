Update and build convenience script.
=========

Compatibility:
---------
* 0AD Empires Ascendant | Empires Besieged,
* 0BC Time Machine (old build system).


Usage:
---------
Before first run set executable flag:
    chmod +x /path/to/buildengine_on_linux.txt

Minimal (assumes location is $HOME/0ad/, no repository update):
    ~/CoM/buildengine_on_linux.txt

    ~/CoM/buildengine_on_linux.txt --update

Specific:
    ~/CoM/buildengine_on_linux.txt --prefix=$HOME/0ad/ --update_repo --update_params='0ad master'

Complete:
    /path/to/buildengine_on_linux.txt --prefix='$HOME/0ad' --debug -j2 --clean --update_repo --update_params='0ad master'"

For SVN append parameter:
   --svn


