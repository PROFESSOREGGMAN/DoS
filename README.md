# LeDoS

[![Build Status](https://travis-ci.org/PROFESSOREGGMAN/LeD-DoS.svg?branch=master)](https://travis-ci.org/PROFESSOREGGMAN/LeD-DoS)

LeD-DoS is a light weight DoS / DDoS tool which can flood an ip with a PoD "Ping of Death" attack from many computers using node.js and a simple web server

  - Simple
  - Html, PHP, JS and Node
  - Open source

# New Features! - (5/19/19)

  - Final updates to Control Panel
  - Fixed issues with loading IP
  - Working Build

### Installation and Use

LeDoS requires [Node.js](https://nodejs.org/) v11.10+ to run.

Install the project and dependencies than config bot.js and Web server.

```sh
$ git clone https://github.com/PROFESSOREGGMAN/LeD-DoS.git LeDoS
$ cd LeDoS
$ cd Bot
$ nano bot.js
```

Inside the dos.js you will find request('http://loaclhost/......') replace the http://localhost with a website that is able to run the dos.php, ip.txt and active.txt files. You can also use localhost but it will need to be port forward to be available with outside computers. ex: http://localhost/DoS/dos.php:8080

### Todos

 - install to PC without detection
 - End Attack and kill background process

License MIT
----

Copyright (c) 2019 Nostalgic NukeZ

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
