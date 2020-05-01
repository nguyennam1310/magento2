
Import database mới mysql -u username -p magento < magento.sql

Cho file đã tải vào htdocs (xampp) chạy lệnh:

php bin/magento setup:upgrade

php bin/magento setup:static-content:deploy -f

php bin/magento indexer:reindex

php bin/magento cache:flush
//Trung anh
composer install - để install vendor

errols: There are no commands defined in the "cache" namespace
Step 1 - sudo rm -rf var/di/* var/generation/* var/cache/* var/page_cache/* var/view_preprocessed/* var/composer_home/cache/*
Step 2 - sudo chmod 777 var -R
Step 3 - sudo chmod 777 pub -R
Step 4 - sudo php bin/magento setup:static-content:deploy
Repeat step 2 & 3.
