# Project Setup using Docker locally

# Useful Commands

## Setup Magento 2 project locally

- `composer create-project --repository=https://repo.magento.com/ --ignore-platform-reqs magento/project-community-edition <project-folder> <version>`
- `php bin/magento setup:install --backend-frontname=admin --db-host=mysql --db-name=magento --db-user=magento --db-password=magento --base-url=https://xxx.local.com/ --base-url-secure=https://xxx.local.com/ --use-secure=1 --use-secure-admin=1 --language=en_GB --timezone=Europe/London --currency=GBP --use-rewrites=1 --admin-user=admin --admin-password=admin12345 --admin-email=admin@xxx.local.com --admin-firstname=Admin --admin-lastname=Admin`

## Setup Wordpress only locally

- Checkout `wordpress-php7` branch
- Run command ...