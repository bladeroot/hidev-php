hiqdev/hidev-php
----------------

## [0.4.3] - 2016-10-17

- Changed `update` action: moved to hidev StartController

## [0.4.2] - 2016-07-31

- Added use of `hidev-chkipper`

## [0.4.1] - 2016-06-16

- Added back `.gitignore` to default goal
- Added allow failure for PHP 5.5

## [0.4.0] - 2016-05-21

- Changed: redone to `composer-config-plugin`
- Removed `CHANGELOG.md` and `.hidev/commits.md` from default goals

## [0.3.4] - 2016-04-13

- Fixed build with asset-packagist

## [0.3.3] - 2016-04-13

- Changed to `hidev-config` <- `extension-config`

## [0.3.2] - 2016-03-30

## [0.3.1] - 2016-01-17

- Added `composer --version` after composer self-update on travis `before_install`

## [0.3.0] - 2016-01-15

- Fixed tests
- Added composer self-update on travis `before_install`
- Added general `install` and `update` goals
- Changed hidev-travis-ci -> hidev-travis
- Changed deps -> before
- Changed: redone with yii2-extraconfig

## [0.2.1] - 2015-12-23

- Added Travis `after_script` upload coverage to Scrutinizer

## [0.2.0] - 2015-12-23

- Added Scrutinizer badges
- Changed php-cs-fixer config to level psr2 only, else moved to `hiqdev/hidev-vendor`

## [0.1.7] - 2015-12-15

- Fixed phpdoc options for php-cs-fixer
- Fixed tests

## [0.1.6] - 2015-12-14

- Changed Travis build: dont build 5.4 and dont allow failure 7

## [0.1.5] - 2015-11-26

- Added tests and coverage

## [0.1.4] - 2015-11-24

- Added Travis CI integration
- Changed default test system to phpunit and added `build` goal
- Added very basic testing
- Added PHPUnit integration

## [0.1.3] - 2015-11-18

- Fixed php-cs-fixer settings: disabled `return`, `empty_return` and `phpdoc_no_empty_return` fixers
- Changed: redone to `hidev-php`

## [0.1.2] - 2015-11-06

- Fixed php-cs-fixer config: dont touch aligning for equals and double arrows

## [0.1.1] - 2015-11-06

- Changed PHP-CS-Fixer options: disabled `align_double_arrow`

## [0.1.0] - 2015-10-24

- Added README badges for Packagist and VersionEye

## [0.0.5] - 2015-10-15

- Added README Installation section template

## [0.0.4] - 2015-09-09

- Added basic Class.php generation with: hidev gen Class

## [0.0.3] - 2015-08-23

- Added skip `vendor` and `web/assets` from fixing
- Fixed project description

## [0.0.2] - 2015-08-17

- Changed to be usable for any vendor
- Fixed dependencies for `all` goal

## [0.0.1] - 2015-07-11

- Changed config: redone parent to plugins
- Inited

## [Development started] - 2015-07-09
