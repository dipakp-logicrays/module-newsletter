# module-newsletter
Magento 2x Newsletter adding new field Guest First Name, Guest Last Name and Privacy agreement checkbox to frontend newsletter form.
=======
Magento 2 Newsletter module overview 
=========================================

Magento 2x Newsletter adding new field Guest First Name, Guest Last Name and Privacy agreement checkbox to frontend newsletter form.

Module is tested on Magento 2.4.2-p1 version


How install module 
==================

1. First download the Magento module (LR_Newsletter) from the github and unzip the
module

2. Use the Ftp client to upload or copy to extension in your [magento_root]/app/code directory

3. After upload module path will be [magento_root]/app/code/LR/Newsletter

4. Open the command line (connect ssh) and go to the Magento root directory then execute
one by one below commands:

    ```bash
    php bin/magento setup:upgrade
    php bin/magento setup:static-content:deploy -f
    php bin/magento indexer:reindex
    php bin/magento cache:clean
    php bin/magento cache:flush
    chmod -R 777 var/ pub/ generated/
    ```

THANK YOU!

