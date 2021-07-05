# ASBC
*Another Simple Bitwarden Client*

## About

As the name says, ASBC is just a simple Bitwarden Client written in Javascript based on Node.js and
Electron. It's actually nothing more than a chromium platform displaying the Bitwarden Web Vault.
I just made this for myself, but if you wanna use it free to do so.


## Installation (i guess)

In the bin directory of this repository there are 3 folders.

```deb```<br/>
This directory contains a package installer for Debian and it's based distros (such as Ubuntu, Linux Mint, etc.)

```rpm```<br/>	
This directoy contains a package installer for Redhat Linux and it's based distros (such as Fedora, CentOS, etc.)

```linux```<br/>
This directory contains the binary executable for linux and essential files archived in a ```.tar.gz``` file. In order to set it up you have to do the following:

* Extract the ```.tar.gz``` archive
* Run the ```setup.sh``` script file. 
* Done!


## Building

In case you want to build ASBC you have to do the following things:<br/>

* Go into the ```src``` folder.
* Extract the ```node_modules.tar.gz``` archive.
* Run ```npm run make``` to build the executable
* Done!
