PHPainfree Functional Changelog
===============================

Version 0.3.0
-------------
**May 13, 2010** *(a mere 30 minutes after v0.2)*

I realized a fatal design flaw mere moments after upgrading my own site from v0.1 to v0.2. Upgrading Painfree.php overwrote $PainfreeConfig, and I lost all of my custom settings for my site. So, to aleviate this problem, I proudly bring you v0.3! **Now With 100% Less Data Loss!**

1. Pulled $PainfreeConfig out of Painfree.php and placed it in PainfreeConfig-GENERIC.php.
2. Painfree.php now REQUIRES a file to exist called PainfreeConfig.php in the includes/ directory.
3. Painfree.php also really hopes (with all of it's might) that PainfreeConfig.php has a variable called $PainfreeConfig defined. 
4. Installation instructions tweaked to reflect the new structure.

*Running an actual Open Source project is hard. Before, I was just write whatever I want and hope for the best. Now I have to actually think about things like upgradability, installation, documentation, and other such silly things. To all 9 people (1 of whom I'm pretty sure is my mother) who "watch" the github repository: sorry for nothing thinking about this earlier...*

Version 0.2.0
-------------
**May 13, 2010**

1. Added CHANGELOG.md to central github master.
2. Added markdown formatting to README file (README.md)
3. Added $Painfree->debug() method to store debugging information.
4. Added generic debug template for ease of development.

Version 0.1.0
-------------
**April 21, 2010**

1. Initial release. Limited functionality provided. 