# Mac Change
![all text](https://github.com/dioxfile/Network-Scripts/raw/master/Mac_Change/QR_Mac.png)

This code aims to validate the Mac quickly and easily.

It uses the 'dialog' program to have a more user friendly interface, making it easier to use and thus reducing the chances of errors.

# What do you need to use this software?
- You will need the 'dialog' program installed on your machine.<br/>
Dialog is a program used to design user-friendly interfaces, with buttons and menus, from a Shell Script.

# How to use it?
You should first check if you have the dialog installed.<br/>
Call the program by its terminal like command:<br/>
`$dialog`<br/>

If you have a return as:<br/>
`$ Unknown command dialog`<br/>
So you do not have the program installed<br/>

To install it on Debian-based distributions simply use the command:<br/>
`$sudo apt install dialog`<br/>

To install it on Arch-based distributions simply use the command:<br/>
`sudo pacman -S dialog`<br/>

To install it on Red Hat-based distributions simply use the command:<br/>
`sudo dnf install dialog`<br/>

Execution permission to MAC.sh with the command<br/>
`$sudo chmod +x Mac.sh`<br/>

After that you just run the program:<br/>
`./Mac.sh`

