# WP Plugin Dev

This is my WordPress plugin development environment. It uses the latest bleeding edge WordPress version to future-proof plugins. 

Plugins exist in separate repositories and are symlinked into the plugins directory.

## Installation

1. Get [Composer](https://getcomposer.org)
1. Run `composer install` to get the latest stable version of WordPress with the Beta Tester plugin
1. Set up WordPress locally and then activate the Beta tester plugin
1. Enable _Bleeding edge nightlies_ in the Beta Tester settings and then update WordPress like you normally would
1. Symlink your plugin(s) into `wordpress/wp-content/plugins` and start testing!
