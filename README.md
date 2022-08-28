# SASS Conversion Assistance

This command allows you to save locations and file names of your SCSS files and reuse them with one command.

    conv

## How to install

Download the repository into your computer.
Enter these two commands:

    cd ./sass-extension

    sass-extension-install

And then happy coding

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
