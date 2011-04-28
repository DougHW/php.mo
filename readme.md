php.mo 0.1 by Joss Crowcroft (http://www.josscrowcroft.com)
=====

Converts gettext translation '.po' files to binary '.mo' files in PHP.

(better readme coming soon.)

**Usage:**

`<?php require('php-mo.php'); phpmo_convert( 'input.po', [ 'output.mo' ] ); ?>`

**NB:**

* If no $output_file specified, output filename is same as $input_file (but .mo)
* Returns true/false for success/failure
* No warranty, but if it breaks, please let me know

**More info:**

https://github.com/josscrowcroft/php.mo

**Credit:**

Based on php-msgfmt by Matthias Bauer (Copyright &copy; 2007), a command-line PHP tool
for converting .po files to .mo. ([http://wordpress-soc-2007.googlecode.com/svn/trunk/moeffju/php-msgfmt/msgfmt.php](http://wordpress-soc-2007.googlecode.com/svn/trunk/moeffju/php-msgfmt/msgfmt.php))

**License:**

GPL v3 http://www.opensource.org/licenses/gpl-3.0.html


kthx.