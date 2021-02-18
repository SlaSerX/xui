``` XtreamUI Portal road warrior installer for Ubuntu

This script will work on Ubuntu and probably other distros of the same families, although no support is offered for them.
It isn't bulletproof but it will probably work if you simply want to setup a XtreamUI Portal on your Ubuntu box. It has been designed to be as unobtrusive and universal as possible.

This is a free shell script under GNU GPL version 3.0 or above Copyright (C) 2017 LinuxHelps project.

Feedback/comment/suggestions : https://slaserx.dev Author Ivan Bachvarov a.k.a SlaSerX

Script work only on Clean Ubuntu install servers

#changelog

XtreamUI auto install script v1.0.1 - RELEASE

* Last XtreamUI Version 22f Mod 18
* Removed all Backdoors
* Patched Version 1.0rc
* Last ffmpeg git version
* Added new mag devices support
* Fix bugs
* Links for download changed
* Implemented support for Ubuntu 18
* fix problem with phing
* Patch composer
* Fix bugs
* Update links

#Install

upload xui.zip file on your server
unzip xui.zip
cd xui
chmod +x install
run with root ./install

# Last ffmpeg git version

* Fully patched for xtream-codes streaming panel
* Nvenc support
* libdfk for aac encoding

Simply replace binaries (ffmpeg, ffprobe) in /home/xtreamcodes/iptv_xtream_codes/bin
(If you cannot replace, rename your old binaries first)

