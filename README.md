# Specifying a package repository
See composer.json file

1. Add "VENDOR_NAME/PACKAGE_NAME": "dev-master" to the list of "require" key-values
2. Add a json object to the "repositories" list with "type": "vcs" and  "url": "PACKAGE_REPO_URL"

See [Composer documentation](https://getcomposer.org/doc/02-libraries.md#publishing-to-a-vcs) for more information.
