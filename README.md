#Minimee<sup>2</sup>

Minimize, combine & cache your CSS and JS files. Minify your HTML. Because size (still) DOES matter.

* [Full Documentation](https://johndwells.github.io/Minimee)
* [On @devot-ee](http://devot-ee.com/add-ons/minimee)
* [Forum Support](http://devot-ee.com/add-ons/support/minimee/)


# Description

> "Minimee combines and compresses JavaScript and CSS files, thereby reducing file sizes and HTTP requests, and turning your puddle of online molasses into a digital fire hose."<br/><small>- Stephen Lewis, founder, [Experience Internet](http://experienceinternet.co.uk/)</small>

Minimee watches your filesystem for changes to your CSS & JS assets, and automatically combines, minifies & caches these assets whenever changes are detected. It can also detect changes to stylesheet templates (whether saved as files or not).

Version 2's substantial re-write has ushered in a host of changes big and small. It is the same Minimee you've come to rely on, with more power, intelligence, and fun-ness.

Minimee is inspired and influenced by [SL Combinator](http://experienceinternet.co.uk/software/sl-combinator/) from Experience Internet, and [Carabiner Asset Management Library](http://codeigniter.com/wiki/Carabiner/) from Tony Dewan.

# Installation

1. Copy folder `/system/expressionengine/third_party/minimee` to your site's own system third_party folder
2. Create a folder, __above webroot__, for Minimee to save your cached files to, e.g. `public_html/cache`
3. Install Minimee's extension, __or__ amend your `config.php` to configure the cache folder's location & url
4. If you wish to enable compression, copy the contents of `sample.htaccess` to an htaccess file placed in your cache folder, e.g. `public_html/cache/.htaccess`

Consult the [full documentation](https://johndwells.github.io/Minimee) for more information.

## Companion Add-Ons

The architecture of Minimee2 has given me the opportunity to build other add-ons that extend Minimee's capabilities.  So if you're curious, have a look at:

* [MSMinimee](https://github.com/johndwells/MSMinimee) - a module that brings full MSM-compatibility to Minimee

## Want Bleeding Edge?

The master branch will always contain the "stable" release of Minimee, where the version number should match what is listed on the [Full Documentation](http://johndwells.github.com/Minimee) page, as well as [on @devot-ee](http://devot-ee.com/add-ons/minimee) and on my [personal website](http://johndwells.com/software/minimee).

To follow development of Version 2.x, refer to the [version2 branch](https://github.com/johndwells/Minimee/tree/version2). Note that version increments will always happen at the master branch first.