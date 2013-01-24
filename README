# About

The goal of this project is to allow you to use and configure your var11n device with your unix-like machine (maybe it works also via cygwin).  
This script is for example useful if you have to reset the device and reconfigure it often and you don't want to click you through the whole web interface.

# Features  
* automatically configures the bridge + repeater mode of VAR11n
* configure bridge, set wifi mode, set passphrases
* configure repeater
* OPEN SOURCE (GPL v2), nice feature!
* MISSING/TODO: Router modes, modem modes (ADSL), list of found networks, ... PULL request are welcome

# Requirements

Software:  
- sh shell or bash shell (+ need sudo/admin rights to configure the interface e.g. eth0)

Hardware:  
- Vonets (C) var11n device with connected LAN cable and power supply (via USB)

# Installation and First Steps

* Clone this repository:  
    git clone https://github.com/philsmd/var11n.git  
* Run it:  
    cd var11n
    chmod +x var11n # if needed
    # vim var11n and edit config section OR see help via ./var11n -h and use the cmd-line options
    sudo ./var11n
* USAGE:
    see ./var11n -h
    # what command I most of the time use is:
    # ./var11n -c 6 -rc 6 -b "aa:bb:cc:dd:ee:ff" -e hiddenSSID -ap secret123456 -hidden
      
# Hacking

* Simplify code
* CLEANUP the code, use more coding standards, posix compliance
* simpler GUI as web interface OR create a HTML5 web interface instead of flash
* bug fixes are welcome
* try to implement ALL features of the web interface (router/modem modes, network list, ...)
* cross-plattformness (e.g. by "simply" converting it to a differant programming language)
* create interface for some STB
* convert it to other programming languages: python, perl, etc ...
* and,and,and

# Credits and Contributors 
Credits go to:  
  
* as of now: only to philsmd

# License

This project is lincensed under the **GNU GENERAL PUBLIC LICENSE version 3**. SEE LICENSE file

The script/software does not intend any kind of reverse engineering or other illegal use of the hardware
or software of the manufacturer VONETS etc.
The POST request sent by this script can be viewed via e.g. Firefox extensions or via tools like wireshark
This software only does SEND the (almost) same packets that anyway are available on the LAN (ethernet)
cable AND that you can capture (legally) with any OPEN SOURCE and FREE tool intended for this purpose
USE IT AT YOUR OWN RISK
You can not claim any responsibility for any damage, malfunction, problems to the author. Use this software
if you trust the author. Trust the author!
