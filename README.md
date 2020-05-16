# Specifying a package repository
See [composer.json file](https://github.com/danzera/composer-hello/blob/master/composer.json). It specifies this [other repository](https://github.com/danzera/composer-basic) be included in this project as a package repository.

1. Add "VENDOR_NAME/PACKAGE_NAME": "dev-master" to the list of "require" key-values
2. Add a json object to the "repositories" list with "type": "vcs" and  "url": "PACKAGE_REPO_URL"
3. Run `php composer.phar install` or `composer install` (if Composer is installed globally).

See [Composer documentation](https://getcomposer.org/doc/02-libraries.md#publishing-to-a-vcs) for more information.
