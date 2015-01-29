#My Emacs Configuration
This is my constantly evolving Emacs configuration.

#Requirements
Emacs 24 or greater.

#Installation
To install the configuration on your system, clone this repository and then link the configuration direcotory (emacs.d) into your home directory. Detailed directions are listed below for Unix and Windows systems.

##For Unix style OS: (Linux/Mac OS X/etc.)

###Clone the repository
    $ cd ~
    $ git clone https://github.com/mrxcitement/emacsrc.git ~/src/emacsrc

###Link the emacs configuration directory
    $ cd ~
    $ ln -s ~/src/emacsrc/emacs.d ~/.emacs.d

##For windows based OS: (Windows XP or greater with MKLINK available)

###Clone the repository from github.
    > cd /d %userprofile%
    > git clone https://github.com/mrxcitement/emacsrc.git %userprofile%/src/emacsrc

###Link the emacs configuration directory.
(Note: To use MKLINK you need to be in a command prompt "Run As" an Administrator.)

    > cd /d %userprofile%
    > mklink /d .emacs.d %userprofile%\src\emacsrc\emacs.d
