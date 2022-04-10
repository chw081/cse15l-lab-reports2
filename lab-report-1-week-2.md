# Week2 Lab Report
## Installing VScode
Go to **Visual Studio Webpage** [click here](https://code.visualstudio.com/) and follow instructions to install on your device.
![Image](VSCInstalling.jpeg)

## Remotely Connecting
This step connects our device to a remote computer.

1. Know your course account
2. Open the terminal in your VScode
3. Use  *"$ ssh cs15lsp22zz@ieng6.ucsd.edu"*  and replace "zz" with your account name
4. type *"yes"* to the messages you recieve and then type your password when it is being asked
![Image](RemmotelyConnecting.jpeg)

## Trying Some Commands
Now we can try some commands and understand their meanings so that we can get around the terminal more effciently in the future. 
* __cd directoryname__ (move to a directory, to move up use ..)
* __ls directoryname__ (displays files in the given directory; type only ls to see explicit files in the current directory; type -a all files, including hidden files in the current directory; -lat shows all the files, including hidden ones, with more information on each one and puts them in time order.)
* __cat filename__ (displays all contents in the given file)
![Image](TryingCommand.jpeg)

## Moving Files with scp
1. Create the file for later use
2. Use command line _(scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/)_
![Image](CopyingFile.jpeg)

## Setting an SSH Key
Using an public SSH key allows the user to enter their computer without a password. 
1. use _($ ssh-keygen)_ without the $ to get the public
2. enter the file path of the file that you want to save the key to
3. press enter a few times until you see codes like the following:

![Image](SSHkey.jpeg)

## Optimizing Remote Running
Using procedures to skip entering password, combine commands in one line and repeat previous command.
![Image](SSHkey2.jpeg)