# dokuwiki-plugin-authdjango

## Using this Plugin

* Be sure that you have the sqlite extension installed and enabled for PHP (using PDO). Normally this is done (in Debian) using 

`sudo apt-get install php-sqlite3`

* In your Django database, make sure (if you're migrating) that your users have the same groups defined. At least, you may want to put at least one user into the 'admin' group, since that is normally how it is defined in Dokuwiki before.
