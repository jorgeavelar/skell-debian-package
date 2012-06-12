Skell Debian Package
====================

Simple structure of a package debian or ubuntu.


Some cool packages to start playing
-----------------------------------
sudo aptitude install build-essential autoconf automake autotools-dev dh-make debhelper devscripts fakeroot xutils lintian pbuilder equivs


Create new control, if necessary
--------------------------------
equivs-control control


Structure of a package name
---------------------------
myapp_0.1.0-stable-ubuntu1204_amd64.deb


Create package
--------------
dpkg -b myapp_0.1.0-stable-ubuntu1204_amd64


Install package
---------------
dpkg -i myapp_0.1.0-stable-ubuntu1204_amd64.deb


Remove package and files
------------------------
sudo apt-get -y remove --purge myapp
