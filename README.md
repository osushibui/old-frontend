## old-frontend

This is Shibui's deprecated frontend, written in PHP which is used purely for  the admin panel.
But, since the code is here just for reference, I don't think it's a huge problem.

- Origin: https://github.com/osuakatsuki/old-frontend
- Mirror: https://github.com/osuripple/old-frontend

## Installation
Copy config.sample.php as config.php and edit it
```
$ cd inc
$ cp config.sample.php config.php
$ nano config.php
```
Then, clone phpmyadmin so we can access it at old.domain/phpmyadmin
```
$ cd ..
$ ln -s /usr/share/phpmyadmin phpmyadmin
```
Then, run composer install on the main directory
```
$ composer install
```

## License
All code in this repository is licensed under the GNU AGPL 3 License.  
See the "LICENSE" file for more information
