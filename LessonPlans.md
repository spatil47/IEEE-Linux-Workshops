# Week 1: Introduction/Background, Linux Installation
- VirtualBox Machine Images --- have students install VirtualBox on their computers, and have them download and install the prebuilt machine images.
  - The VirtualBox images will be Ubuntu Linux.
  - We'll bring the machine images in on flash drives for those students who don't download the images before workshops start

# Week 2: Terminal Commands, Filesystem Structure
- Filesystem navigation (`ls`, `cd`, `pwd`, etc.)
- Reading/viewing files (`cat`, `more`, `less`, etc.)
- Writing/editing files (`vi`, `nano`, redirects, etc.)
- Reading/viewing system internals (navigating the `/sys` and `/proc` directories, and reading their contents)
- Installing and uninstalling programs (`apt-get` and its functions)

# Week 3: Shell Scripting
- Intro to writing shell scripts for `bash`

## Assignment ideas
- Write a shell script to print "Hello, World!" to the screen and exit.
- Write a shell script for keeping a textfile-based diary --- script should open a text file in a predefined directory; the text file is named according to the current date and possibly the time too.
- Write a shell script that organizes files into directories based on the files' creation times --- the directories will be named after the sorted files' creation times, and the script will accept dates as arguments.