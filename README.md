# THE BOX

v0.2.1

## SUMMARY

A simple script that installs 174 useful Linux tools for penetration testing and security audits.

## DESCRIPTION

This script was written in a way that you could install a brand new OS and, by running it, you would be ready to start all your penetration testing without the hassle of installing each tool one by one.

We have a couple of options: `-m` or `--minimal` only installs the most common tools for each category (nmap, wireshark, dirb, metasploit, etc.) and `-ng` or `--no-gui` only installs tools that don't require a GUI, for an even lighter pentest environment. Without any flags it will install 177 total tools from security utilities such as UFW, Anonsurf, KeePassXC, to (post-)exploitation frameworks like Metasploit, Empire and PowerSploit.

This program stores the downloaded tools in multiple folders, regarding the type of utility being installed:

- Reverse Engineering
- Miscellaneous
- Cracking
- Wifi Hacking
- Networking
- OSINT
- Forensics
- Security
- Enumeration
  - Fuzzers
  - Scanners
- Exploitation
- Post-Exploitation
- Wordlists

Disclaimer: Some downloads and/or installations might fail. You need to ensure that you have internet connection, enough disk space and admin (root) privileges. Besides that, some packages or links might not be available when trying to download them.

## SYSTEM REQUIREMENTS

- AMD64
- Debian based (Ubuntu, Linux Lite, Xubuntu...)
- x64

## EXECUTION

Terminal execution:

```bash
$ git clone https://github.com/cycurity/the-box.git
$ cd the-box
$ chmod +x install
$ ./install -h
```

## CREDITS

Development team:

- [nu11pointer](https://github.com/nu11pointer "nu11pointer's Github Profile")
- [intMa1n](https://github.com/Bernardo15Sousa "intMa1n's Github Profile")
- [Oz0nO](https://github.com/Oz0nO "Oz0nO's Github Profile")

External Sources:

- [pollev](https://github.com/pollev "polev's GitHub Profile") - [Bash Progress Bar](https://github.com/pollev/bash_progress_bar)
- [cxw42](https://github.com/cxw42 "cxw42's GitHub Profile") - [Bash Progress Bar](https://github.com/pollev/bash_progress_bar)

## LICENSE

Copyright (C) 2021, Cycurity

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

The software is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

Check out the GNU General Public License: [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/ "GNU General Public License")
