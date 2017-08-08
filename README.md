# Sample Composer Package
This project is a concrete5 sample package that is powered entirely by [composer](https://getcomposer.org).

To install this package on a [composer based concrete5](https://github.com/concrete5/composer) site, make sure you already have `composer/installers` then run:

```sh
$ composer install concrete5/sample_composer_package
```

Then install the package

```sh
$ ./vendor/bin/concrete5 c5:package-install sample_composer_package
```


----

# Using this project as a skeleton

First, use `composer create-project` to begin your own package project.

```php
$ composer create-project concrete5/sample_composer_package
```

Once this is done, modify the `composer.json` to have information about your project and an updated name.
Then set up your VCS

```php
git init
git remote add origin git@github.com/youraccount/yourrepository
git add .
git commit -m "Initial Commit"
git push
```

Finally, add your git repository to a [composer repository](https://packagist.org/). And that's it!
