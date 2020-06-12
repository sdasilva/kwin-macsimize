# kwin-macsimize
This is a fork of Aetf kwin-maximize-to-new-desktop. [Link to his work](https://github.com/Aetf/kwin-maxmize-to-new-desktop).

MACsimize is a KWin script that moves maximized windows to a new virtual desktop, moves back to original desktop if restored or closed. Each window takes place on a new virtual desktop, there's no need to add desktops manually.

## Screenshot
![Screenshot](doc/MACsimize.gif)

## Change Log
See [CHANGELOG.md](CHANGELOG.md).


** Installation:

   #+BEGIN_SRC bash
   git clone https://github.com/sdasilva/kwin-macsimize.git
   cd kwin-macsimize/
   plasmapkg2 --type kwinscript -i .
   #+END_SRC
   
   or if updating
   
   #+BEGIN_SRC bash
   plasmapkg2 --type kwinscript -u .
   #+END_SRC

** Usage:
   Install

   Activate the script using ~kcmshell5 kwinscripts~
