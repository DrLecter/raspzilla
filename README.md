Raspzilla
=========

Raspzilla is an SD card imaging/cloning program similar to Clonezilla.

Requirements
------------

- **bash** ( mine is >=4, should work with any modern version )
- **pv** (Shell pipeline element to meter data passing through)
- **dd** (convert and copy a file, part of GNU **coreutils**)
- **dialog** or ** whiptail** (user friendly dialogs for shell scripting)


Downloading Raspzilla
---------------------

    git clone https://github.com/DrLecter/raspzilla.git

Installing Raspzilla
--------------------

Copy or link the `raspzilla` file to anywhere in your path (/usr/local/bin would do), 
and make sure it can be executed as root.

Configuring Raspzilla
---------------------

This script needs you to manually edit where the image files are.

DISCLAIMER
==========

I've put this together in a couple of minutes, in order to ease my needs of 
managing, imaging and cloning SD Cards for many Raspberry-based custom projects 
I work with for my organization. My workstation runs Debian 9  and images are 
Raspbian based. If your software is different, your mileage my vary.
