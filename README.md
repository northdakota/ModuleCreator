# Magento 2 Module Creator #
Introducing you a simple Magento 2 module creator.

### Installation ###
Simply clone or download and unpack module to your Magento 2 app/code folder(full path should looks like - 'app/code/Ihb/ModuleCreator').
Then go to Magento 2 root folder and run 'php -f bin/magento setup:upgrade' to activate Module Creator.

#### How to use ###
After Module Creator activated, just run 'php -f bin/magento ihb:module-create Vendor_Module' command. This will
create simple module structure in app/code/Vendor/Module folder.

### Test Controller ###
You can test your module in test controller. Go to http://<your-domain/<vendor><moduleName>/index/index url.

### Contributing ###
Feel free to change anything you want to increase Module Creator functionality.

