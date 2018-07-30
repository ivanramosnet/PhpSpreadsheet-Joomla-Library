# PhpSpreadsheet Library for Joomla!

**PhpSpreadsheet Library for Joomla! 3.x**

If you already know how to use PhpSpreadsheet and you need it for a Joomla! project, than this is a library package to be used in Joomla! Easy to install and update.

Download
--------

[![Download now](https://raw.github.com/vdespa/PhpSpreadsheet-Joomla-Library/master/download.png)](https://bitbucket.org/vdespa/phpexcel-joomla-library/downloads/PhpSpreadsheet-Joomla-Library-1.8.0.zip)

You can download the current version / older version of PhpSpreadsheet-Joomla-Library using the [PhpSpreadsheet-Joomla-Library download page] (https://bitbucket.org/vdespa/phpexcel-joomla-library/downloads).

Version
-------

* The current Joomla! Library is using PhpSpreadsheet 1.2.

Usage
-----

    // Import PhpSpreadsheet library
    jimport('phpspreadsheet.library');

or 

    require_once JPATH_LIBRARIES . '/phpspreadsheet/library.php';


Now you can create a new Excel document:

    $PhpSpreadsheet = new PhpSpreadsheet();



Documentation
-------------

* [PhpSpreadsheet Codeplex page] (http://phpexcel.codeplex.com/)
* [PhpSpreadsheet github page] (https://github.com/PHPOffice/PhpSpreadsheet)

Automatic updates
-----------------

This library is integrated with Joomla's automatic updates. Before updating it's mandatory that you check that your documents still work as expected.

Please note that PhpSpreadsheet releases from the 1.x will NOT get an automatic upgrade to PhpSpreadsheet 2.0.0 (when released).

Bugs? Problems? Feedback?
-------------------------

If you have any problems installing / updating PhpSpreadsheet Library in Joomla! feel free to [Add a New issue] (https://github.com/vdespa/PhpSpreadsheet-Joomla-Library/issues)

If you are having problems with PhpSpreadsheet itself and you think is a bug or something, check the [PhpSpreadsheet Issue Tracker] (https://github.com/PHPOffice/PhpSpreadsheet/issues)

Credits
-------

* Special thanks to the [PHPOffice team] (https://github.com/PHPOffice?tab=members) which put the PhpSpreadsheet library together.
* Also thanks to Joe for the [inspiration] (http://www.ostraining.com/howtojoomla/how-tos/development/how-to-package-joomla-libraries).


License
-------
PhpSpreadsheet is licensed under [LGPL (GNU LESSER GENERAL PUBLIC LICENSE)](https://github.com/PHPOffice/PhpSpreadsheet/blob/master/license.md)
