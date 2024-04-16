# Upgrade Instructions

The current codebase is implemented to work with PHP version 5 and MySQL version 5. To ensure compatibility with the latest features and security updates, the following upgrades are required:

- Upgrade PHP to version 8.3.
- Upgrade MySQL to version 8.

Please note that upgrading to these versions may require changes to the code to ensure compatibility. It is recommended to review the PHP and MySQL migration guides and perform thorough testing after the upgrade.

## PHP Upgrade

1. Check the PHP migration guides for any backward incompatible changes: https://www.php.net/manual/en/migration8.php
2. Update the server's PHP version to 8.3 using the appropriate package manager or software repository.
3. Review and update the codebase to resolve any compatibility issues with the new PHP version.
4. Test the application thoroughly to ensure all features are working as expected.

## MySQL Upgrade

1. Review the MySQL upgrade guide for important changes and considerations: https://dev.mysql.com/doc/refman/8.0/en/upgrading.html
2. Backup the current MySQL databases before proceeding with the upgrade.
3. Update the server's MySQL version to 8 using the appropriate package manager or software repository.
4. Run the MySQL upgrade scripts to update the system tables.
5. Test the application with the new MySQL version to ensure data integrity and functionality.

Please coordinate with the server administrator to schedule and perform the upgrades during a maintenance window to minimize downtime.

