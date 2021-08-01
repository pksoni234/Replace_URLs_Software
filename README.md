# Replace URLs Software

This script was made to aid the process of migrating PHP and MySQL based websites. It has additional features for WordPress and Drupal but works for most other similar CMSes.

If you find a problem let us know in the issues area and if you can improve the code then please fork the repository and send us a pull request :)

## Warnings & Limitations

1. Three character UTF8 seems to break in certain cases.
2. We can't test every possible case, though we do our best. Backups and verifications are important.
3. The license for this script is GPL v3 and no longer WTFPL. Please bear this in mind if contributing or branching.
4. You use this script at your own risk and we have no responsibility for any problems it may cause.
5. *Do backups.*

## Usage

1. *Do backups.*
2. Migrate all your website files.
3. Upload the script folder to your web root or higher.	
4. Browse to the script folder URL in your web browser.
5. Fill in the fields as needed.
6. Choose the `Dry run` button to do a dry run without searching/replacing.

## Installation

If you would like Search Replace DB to detect your WordPress installation, you should install it within a new subfolder within your WordPress installation.

For example, if you have
	
	/website.com/index.php
   
	/website.com/wp-config.php
   
	/website.com/wordpress/
   
	/website.com/wordpress/index.php
   
	/website.com/wordpress/wp-settings.php
   
	etc.