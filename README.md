# latemp

An easy way to organize and reuse latex templatefiles

## Getting started

### Prerequisites

You will need some texteditor and a pdfviewer if on GNU/Linux. Latemp uses a makefile to install.

### Installing

Clone the repository and cd in

```
$ git clone https://github.com/srydell/latemp.git
$ cd latemp
```

Change the default editor and pdfviewer. The default on GNU/Linux is vim and mupdf. On Mac it is texpad. This can be done by changing the first lines in the latemp file. Note that latemp assumes that the GNU/Linux editor is terminal based, and the Mac editor is in your applications folder.

Then you may install latemp. This will copy the latemp file to your /usr/local/bin/ folder so that it is in your PATH variable by default.

```
$ make
```

You may now test it simply by typing

```
$ latemp
```

to find out what your current templates are. These can then be accessed by typing

```
$ latemp templateName
```

this will open your editor and pdfviewer depending on which system you are on.

Good luck!

## Contributing

You are free to do with these files as you wish. If you make improvements along the way, please do a pull request to let me benefit from them aswell!
