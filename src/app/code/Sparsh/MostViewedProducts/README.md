##Most Viewed Products Extension

This extension lets the store owners display most viewed products on their website effectively using block, template, layout, and widget thereby boosting the sales.

##Support: 
version - 2.3.x, 2.4.x

##How to install Extension

1. Download the archive file.
2. Unzip the file
3. Create a folder [Magento_Root]/app/code/Sparsh/MostViewedProducts
4. Drop/move the unzipped files to directory '[Magento_Root]/app/code/Sparsh/MostViewedProducts'

#Enable Extension:
- php bin/magento module:enable Sparsh_MostViewedProducts
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush

#Disable Extension:
- php bin/magento module:disable Sparsh_MostViewedProducts
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush