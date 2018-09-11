# magento-2-additional-css-js
This module let you add css and javascript code in any theme.
It also support Jquery.

# Compatibility
Magento 2.x

# Installation
-Install by Composer :

You can install the module by Composer (If your server supports Composer). Please go to the Magento folder and run the command: composer require hashcrypt/additional-css-js

-Install by uploading files:

Download the zip file and unzip the plugin. Now create folder app/code/Hashcrypt/CssJs and copy all files which you have downloaded to that folder.
Now run below commands to install module,
php bin/magento setup:upgrade
php bin/magento cache:flush

# Configuration
Go to admin panel > Stores > Configuration > Hashcrypt Technologies > Additional Css-Js
Enter custom style and script then save the configuration.
Flush the cache if cache is enabled.
