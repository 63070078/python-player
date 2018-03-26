Python Music Player is no longer under active development. Release 2.5 will come out soon as-is with no guarentees
Believe me, I am working on everything...

I am 99.99% done with release 2.5.

# Python Music Player
A small music player coded in the python programming language

# Dependencies

- Pygame (http://pygame.org) - Required
- AppJar (http://appjar.info) - Required for GUI to work


# Usage

Plays music in the "Music" folder within the current directory

Usage: 

          `player.py [-hvc] [-f <filepath>]`

Options: 

          -h, --help:   Displays this help text
          
          -v, --verbose Displays extra information
          
          -c, --console Disables Pygame screen (text-only mode)
          
          -f, --file    Plays the file at the filepath specified
          
Examples: 

          player.py -c -v -f /file/path/foo.bar

          player.py -f foo.bar
          
# How to install
There is no install (the horror!)
To start the player, run the following commands:

Linux:

`git clone https://github.com/creepersbane/python-player`

`cd python-player`

`./player.py`


Windows:
1. Clone the repository
2. In a terminal, go to the "python-player" directory
3. Run `python player.py`

Mac:
1. Download the .zip file from https://github.com/BenjaminUrquhart/python-player/archive/master.zip
2. Extract the zip
3. In a terminal, go to (download location)/python-player-master
4. Run `python player.py`
