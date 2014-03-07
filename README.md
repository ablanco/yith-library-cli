# Yith Library - Command line interface

[![NPM version](https://badge.fury.io/js/yith-library-cli.png)](http://badge.fury.io/js/yith-library-cli)
[![Dependency Status](https://david-dm.org/ablanco/yith-library-cli.png)](https://david-dm.org/ablanco/yith-library-cli)

Command line interface for [Yith Library](http://yithlibrary.com).

Right now it can only read the contents of a Yith Library backup file,
providing offline access to your protected secrets. Interaction with a remote
Yith Library server is planned for future releases (contributions are
welcome!).

## Installation

This client is build on top of [node.js](http://nodejs.org), it requires
**node.js 0.6** o higher to be present.

This package is intended to be installed system wide, so execute the next
command with root priviledges:

    npm install -g yith-library-cli

When npm finish installing the client, you will have the `yith` command
available.

### Development

First you need to get a copy of the code, just clone the repository:

    git clone git://github.com/ablanco/yith-library-cli.git

When the clone is done, you need to install the dependencies:

    cd yith-library-cli
    npm install -d

And now you are ready to start developing awesome contributions :)

## Usage

    Usage: yith [options] <backup_file>

    Options:

    -h, --help                       output usage information
    -V, --version                    output the version number
    -l, --list                       List passwords
    -s, --search <keyword>           Search secrets
    -d, --decipher <service_number>  Decipher a secret
    -v, --view <service_number>      Show a secret details

## MIT License

Copyright (c) 2013 Alejandro Blanco &lt;alejandro.b.e@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Other licenses

[Console](http://thenounproject.com/noun/console/#icon-No8571) icon designed by
[Austin Andrews](http://thenounproject.com/Templarian) from The Noun Project.
