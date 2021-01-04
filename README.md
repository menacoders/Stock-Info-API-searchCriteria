# Stock Info in Extention attributes
Fix for Magento 2 searchCriteria not returning stock info in product listing/search.

# the issue
"/rest/V1/products?searchCriteria" API endpoint" does not return information about stock in the "extension_attributes" section
https://github.com/magento/magento2/issues/22737

# the solution !
Now it's return all stock info about the products when you are using searchCriteria.

# how to install?
just upload the module files to this directory 
/app/code/Menacoders/Stock

* run these commands *

php bin/magento setup:upgrade
php bin/magneto index:reindex
php bin/magento c:c
php bin/magento c:f


# Contact us:
hello@menacoders.com
www.menacoders.com
www.magentoar.com
