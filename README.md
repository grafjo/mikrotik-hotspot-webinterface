mikrotik-hotspot-webinterface
=============================

This is a custom Bootstrap 3 based webinterface for a Mikrotik Hotspot. For more Details please visit http://wiki.mikrotik.com/wiki/Manual:Customizing_Hotspot

Installation
------------

Clone this repository.
* Create a folder ```js``` and put ```bootstrap.min.js``` from http://getbootstrap.com/, ```jquery.min.js``` from https://code.jquery.com/jquery.min.js into it.
* Copy fonts folder out of the bootstrap archive to root level
* Copy ```bootstrap.min.css``` into css folder
* Connect to your Routerboard via ftp, copy the ```md5.js``` into the ```js``` folder.
* Copy the hole repository folder to your Routerboard.
* Open the WebFig Interface with a browser and go to ```IP > Hotspot > Server Profiles``` and create a new Profile. Under ```HTML Directory``` select ```mikrotik-hotspot-webinterface```.

DONE

Authors
-------

* Johannes Graf ([@grafjo](https://github.com/grafjo))


License
-------

mikrotik-hotspot-webinterface is released under the MIT License. See the bundled LICENSE file
for details.

