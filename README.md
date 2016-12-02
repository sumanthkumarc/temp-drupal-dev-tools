# temp-drupal-dev-tools

Temporarily use the drush, drupal console and composer.

Drupal Console:
// download the drupal console php archive file
``` curl https://drupalconsole.com/installer -LO drupal.phar```
// set executable on your phar file
chmod +x drupal.phar
// Set alias to use
alias dc="/path/to/file/drupal.phar"
// check if its working
dc about

Drush:
// Download the drush phar file. This gives drush 8, supports d6,d7,d8
curl https://s3.amazonaws.com/files.drush.org/drush.phar -LO drush.phar
// set executable on your phar file
chmod +x drush.phar
// Set alias to use
alias drush="/path/to/file/drush.phar"
// check if its working
dru status

Composer:
// Download the composer phar file.
curl -LO https://getcomposer.org/composer.phar
// set executable on your phar file
chmod +x composer.phar
// Set alias to use
alias composer="/path/to/file/composer.phar"
// check if its working
comp -v.
