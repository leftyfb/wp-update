This script is used to update all wordpress instances on a server and send an email if updates were done.
It utilized wp-cli.phar from http://wp-cli.org/. You'll need to install this first and tell wp-update the location of wp-cli.phar.

Usage: /path/to/wp-update <core|plugin|theme|all>

wp-update core # Doesn't update, but alerts you via email that core Wordpress updates are available

wp-update plugin # updates all plugins for all wordpress instances

wp-update theme # updates all themes for all wordpress instances

wp-update all # updates all plugins, themes and core for all wordpress instances
