# avrflasher

The project was moved to https://gitverse.ru/sozykin/avrflasher

This is a simple program for flashing AVR microcontrollers via USB (arduino bootloader) using avrdude.

# Install

If you have problems starting the program, set the environment variable

export QT_DEBUG_PLUGINS=1

Information about the missing libraries will appear. For example, on some computers, the problem was fixed by the commands


Xubuntu:

sudo apt install python3-pip, qtbase5-dev, libxcb-xinerama0, libxcb-icccm4, libxkbcommon-x11-0

Simply Linux:

sudo apt install pip

pip install -r ./requirements.txt
