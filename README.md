tt-rss-yourls
=============

This plugin is known to be working with the lastest stable version of ttrss 1.7.9.
This branch is the 'dev' branch to allow me/you/etc to change code do pull requests without killing the "production/master" branch ;)

A plugin for Tiny Tiny RSS, to shorten urls via Yourls
Requierement
------------
* Obviously a working [Tiny Tiny RSS](http://tt-rss.org/) installation
* Obviously(bis) a working [Yourls](http://yourls.org) installation
* php-curl installed on your environnement
* the will to shorten urls from tt-rss via yourls ;)


Installation
------------
* Copy the *yourls* folder to your tt-rss *plugins/* folder.
* Go to your tt-rss Preference page
* Under *Plugins* section enable yourls plugin
* A new pref pane will show up, named ... *Yourls* ;)
* In there you will have to enter :
* * *Yourls base URL* in the form *http://sho.rt*
* * *Yourls API key* from your installation of yourls


Usage
------
While on an article, you will see a Y shaped Yourls icon. Clicking on it will bring up a dialog with the shortened URL of the article link. Within the dialog icons to chare this shortened link via Facebook and/or Twitter will also be displayed.

ENJOY ! ;)

Info
----
This plugin was originally posted on [this forum thread](http://www.tt-rss.org/forum/viewtopic.php?f=22&t=1429&p=7564) and is initially the work of Beun (has to be said !)



Thanks
------
Thanks to Beun, the original creator of this plugin.
Thank to code contributors :
* [chatainsim](https://github.com/chatainsim)
* [cy8aer](https://github.com/cy8aer)
