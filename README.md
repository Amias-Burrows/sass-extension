# SASS Conversion Assistance

This command allows you to save locations and file names of your SCSS files and reuse them with one command.

    conv

**Important!* This repository doesn't contain sass or a link to it yet so you'll have to go and download it from their repository*

[SASS](https://github.com/sass/sass)

## How to install

**This folder isn't quite ready for downloading yet but if you want to try it out the commands are below**
Download the repository into your computer.
Enter these three commands:

    cd ./sass-extension

    sass-extension-install

    source ~/.bashrc

And then happy coding

The source command is only required if you don't intend on restarting your computer.  This command allows you to use the program straight away from wherever in your file structure you are.

## How to use

To use you simply need to enter the directory your project exists in and type:

    conv --init

or

    conv -i

and then specify the locations of the files you are using such as:

    conv --root ./assets/css/scss/root/
    conv --output ./assets/css/
    conv --file root

When you type the command `conv` the file at the location `./assets/css/scss/root/root.scss` will be saved into the file at the location `./assets/css/root.css`
