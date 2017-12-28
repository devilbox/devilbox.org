# Devilbox
 
**[Quickstart](https://github.com/cytopia/devilbox/blob/master/docs/Quickstart.md)**｜**[Install](https://github.com/cytopia/devilbox/blob/master/docs/Install.md)**｜**[Update](https://github.com/cytopia/devilbox/blob/master/docs/Update.md)**｜**[Configure](https://github.com/cytopia/devilbox/blob/master/docs/Configure.md)**｜**[Run](https://github.com/cytopia/devilbox/blob/master/docs/Run.md)**｜**[Usage](https://github.com/cytopia/devilbox/blob/master/docs/Usage.md)**｜**[OS](https://github.com/cytopia/devilbox/blob/master/docs/OS.md)**｜**[Backups](https://github.com/cytopia/devilbox/blob/master/docs/Backups.md)**｜**[Examples](https://github.com/cytopia/devilbox/blob/master/docs/Examples.md)**｜**[Technical](https://github.com/cytopia/devilbox/blob/master/docs/Technical.md)**｜**[Hacking](https://github.com/cytopia/devilbox/blob/master/docs/Hacking.md)**｜**[FAQ](https://github.com/cytopia/devilbox/blob/master/docs/FAQ.md)**

---


### Dockerized LAMP/MEAN stack

<div class="center">
  <a href="https://github.com/cytopia/devilbox"><img class="battery" title="Devilbox on Github" alt="Github" src="/assets/img/logos/64x64/github.png" /></a>
  <a href="https://hub.docker.com/r/cytopia"><img class="battery" title="Devilbox on Docker Hub" alt="Docker" src="/assets/img/logos/64x64/docker.png" /></a>
</div>
<p class="center">The devilbox is a modern and highly customisable <a href="https://en.wikipedia.org/wiki/LAMP_%28software_bundle%29">LAMP</a> and <a href="https://en.wikipedia.org/wiki/MEAN_(software_bundle)">MEAN</a> stack replacement based purely on docker and docker-compose running on all major platforms. It supports an unlimited number of projects for which vhosts and DNS records are created automatically. Email catch-all and popular development tools will be at your service as well.</p>

<img src="assets/img/devilbox-dash.png" alt="Devilbox"/>


### Supported Host OS

<p class="center">Don't worry about switching computers. The devilbox will run on all major operating systems.</p>

<div class="center">
  <img class="battery" title="Linux support" alt="Linux support" src="https://raw.githubusercontent.com/cytopia/icons/master/64x64/linux.png" />
  <img class="battery" title="OSX support" alt="OSX support" src="https://raw.githubusercontent.com/cytopia/icons/master/64x64/osx.png" />
  <img class="battery" title="Windows support" alt="Windows support" src="https://raw.githubusercontent.com/cytopia/icons/master/64x64/windows.png" />
</div>


### Install, Configure and Start

<p class="center">Your whole development stack is up and running in a few simple steps.</p>

```shell
# Get the soures
$ git clone https://github.com/cytopia/devilbox
$ cd devilbox

# Create and customize the config file
$ cp env-example .env
$ vim .env

# Start your daemons
$ docker-compose up
```


### Run exactly what you need

<p class="center">Choose your required daemons and select a version. Any combination is possible.<br/>This will allow you, to always exactly simulate your production environment locally during development.</p>

<div class="table-scroll">
<table>
  <thead>
    <tr>
      <th>Apache</th>
      <th>Nginx</th>
      <th>PHP</th>
      <th>MySQL</th>
      <th>MariaDB</th>
      <th>PerconaDB</th>
      <th>PgSQL</th>
      <th>Redis</th>
      <th>Memcached</th>
      <th>MongoDB</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a title="Apache 2.2"       href="https://github.com/cytopia/docker-apache-2.2">2.2</a></td>
      <td><a title="Nginx stable"     href="https://github.com/cytopia/docker-nginx-stable">stable</a></td>
      <td><a title="PHP 5.4"          href="https://github.com/cytopia/docker-php-fpm-5.4">5.4</a></td>
      <td><a title="MySQL 5.5"        href="https://github.com/cytopia/docker-mysql-5.5">5.5</a></td>
      <td><a title="MariaDB 5.5"      href="https://github.com/cytopia/docker-mariadb-5.5">5.5</a></td>
      <td><a title="PerconaDB 5.5"    href="https://github.com/cytopia/docker-percona-5.5">5.5</a></td>
      <td><a title="PgSQL 9.1"        href="https://github.com/docker-library/postgres">9.1</a></td>
      <td><a title="Redis 2.8"        href="https://github.com/docker-library/redis">2.8</a></td>
      <td><a title="Memcached 1.4.21" href="https://github.com/docker-library/memcached">1.4.21</a></td>
      <td><a title="MongoDB 2.8"      href="https://github.com/docker-library/mongo">2.8</a></td>
    </tr>
    <tr>
      <td><a title="Apache 2.4"       href="https://github.com/cytopia/docker-apache-2.4">2.4</a></td>
      <td><a title="Nginx mainline"   href="https://github.com/cytopia/docker-nginx-mainline">mainline</a></td>
      <td><a title="PHP 5.5"          href="https://github.com/cytopia/docker-php-fpm-5.5">5.5</a></td>
      <td><a title="MySQL 5.6"        href="https://github.com/cytopia/docker-mysql-5.6">5.6</a></td>
      <td><a title="MariaDB 10.0"     href="https://github.com/cytopia/docker-mariadb-10.0">10.0</a></td>
      <td><a title="PerconaDB 5.6"    href="https://github.com/cytopia/docker-percona-5.6">5.6</a></td>
      <td><a title="PgSQL 9.2"        href="https://github.com/docker-library/postgres">9.2</a></td>
      <td><a title="Redis 3.0"        href="https://github.com/docker-library/redis">3.0</a></td>
      <td><a title="Memcached 1.4.22" href="https://github.com/docker-library/memcached">1.4.22</a></td>
      <td><a title="MongoDB 3.0"      href="https://github.com/docker-library/mongo">3.0</a></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td><a title="PHP 5.6"          href="https://github.com/cytopia/docker-php-fpm-5.6">5.6</a></td>
      <td><a title="MySQL 5.7"        href="https://github.com/cytopia/docker-mysql-5.7">5.7</a></td>
      <td><a title="MariaDB 10.1"     href="https://github.com/cytopia/docker-mariadb-10.1">10.1</a></td>
      <td><a title="PerconaDB 5.7"    href="https://github.com/cytopia/docker-percona-5.7">5.7</a></td>
      <td><a title="PgSQL 9.3"        href="https://github.com/docker-library/postgres">9.3</a></td>
      <td><a title="Redis 3.2"        href="https://github.com/docker-library/redis">3.2</a></td>
      <td><a title="Memcached 1.4.23" href="https://github.com/docker-library/memcached">1.4.23</a></td>
      <td><a title="MongoDB 3.2"      href="https://github.com/docker-library/mongo">3.2</a></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td><a title="PHP 7.0"          href="https://github.com/cytopia/docker-php-fpm-7.0">7.0</a></td>
      <td><a title="MySQL 8.0"        href="https://github.com/cytopia/docker-mysql-8.0">8.0</a></td>
      <td><a title="MariaDB 10.2"     href="https://github.com/cytopia/docker-mariadb-10.2">10.2</a></td>
      <td></td>
      <td><a title="PgSQL 9.4"        href="https://github.com/docker-library/postgres">9.4</a></td>
      <td></td>
      <td><a title="Memcached 1.4.23" href="https://github.com/docker-library/memcached">1.4.24</a></td>
      <td><a title="MongoDB 3.4"      href="https://github.com/docker-library/mongo">3.4</a></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td><a title="PHP 7.1"          href="https://github.com/cytopia/docker-php-fpm-7.1">7.1</a></td>
      <td></td>
      <td><a title="MariaDB 10.3"     href="https://github.com/cytopia/docker-mariadb-10.3">10.3</a></td>
      <td></td>
      <td><a title="PgSQL 9.5"        href="https://github.com/docker-library/postgres">9.5</a></td>
      <td></td>
      <td>...</td>
      <td><a title="MongoDB 3.5"      href="https://github.com/docker-library/mongo">3.5</a></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td><a title="PHP 7.2"          href="https://github.com/cytopia/docker-php-fpm-7.2">7.2</a></td>
      <td></td>
      <td></td>
      <td></td>
      <td><a title="PgSQL 9.6"        href="https://github.com/docker-library/postgres">9.6</a></td>
      <td></td>
      <td><a title="Memcached 1.4.36" href="https://github.com/docker-library/memcached">1.4.36</a></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td><a title="HHVM"             href="https://github.com/cytopia/docker-hhvm-latest">HHVM</a></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td><a title="Memcached latest" href="https://github.com/docker-library/memcached">latest</a></td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>

### Run only what you need

<p class="center">You are not forced to load the whole stack everytime. Only bring up what you really need.<br/>It is also possible to add or remove daemons while the stack is already running.</p>

```shell
# Load traditional lamp stack only
$ docker-compose up httpd php mysql

# Add redis to the running stack
$ docker-compose up redis

# Stop MySQL from the current stack
$ docker-compose stop mysql
```


### Introduction Videos

<p class="center">Head over to youtube for a quick introduction and see for yourself how easily new projects can be created.</p>

<div class="center">
  <a target="_blank" href="https://www.youtube.com/watch?v=reyZMyt2Zzo" alt="Devilbox introduction video" title="Devilbox introduction video"><img src="/assets/img/youtube_01-setup-and-workflow.png" /></a>
  <a target="_blank" href="https://www.youtube.com/watch?v=e-U-C5WhxGY" alt="Devilbox Email catch-all introduction" title="Devilbox Email catch-all introduction"><img src="/assets/img/youtube_02-email-catch-all.png" /></a>
</div>


### PHP Modules

<div class="center">
  <p>The devilbox is a development stack, so it is made sure that a lot of PHP modules are available out of the box in order to work with many different frameworks. There will however be slight differences between the versions and especially with HHVM. To see the exact bundled modules for each version visit the corresponding docker repositories on Github:</p>

  <img class="battery" title="PHP" alt="PHP" src="/assets/img/logos/64x64/php.png" />
  <img class="battery" title="HHVM" alt="HHVM" src="/assets/img/logos/64x64/hhvm.png" />

  <p>
  <strong><a title="PHP 5.4" href="https://github.com/cytopia/docker-php-fpm-5.4">PHP 5.4</a></strong> |
  <strong><a title="PHP 5.5" href="https://github.com/cytopia/docker-php-fpm-5.5">PHP 5.5</a></strong> |
  <strong><a title="PHP 5.6" href="https://github.com/cytopia/docker-php-fpm-5.6">PHP 5.6</a></strong> |
  <strong><a title="PHP 7.0" href="https://github.com/cytopia/docker-php-fpm-7.0">PHP 7.0</a></strong> |
  <strong><a title="PHP 7.1" href="https://github.com/cytopia/docker-php-fpm-7.1">PHP 7.1</a></strong> |
  <strong><a title="PHP 7.2" href="https://github.com/cytopia/docker-php-fpm-7.2">PHP 7.2</a></strong> |
  <strong><a title="HHVM"    href="https://github.com/cytopia/docker-hhvm-latest">HHVM</a></strong>
  </p>
<p>apc, apcu, bcmath, bz2, calendar, Core, ctype, curl, date, dom, ereg, exif, fileinfo, filter, ftp, gd, gettext, gmp, hash, iconv, igbinary, imagick, imap, intl, json, ldap, libxml, magickwand, mbstring, mcrypt, memcache, memcached, mhash, mongodb, msgpack, mysql, mysqli, mysqlnd, openssl, pcntl, pcre, PDO, pdo_mysql, pdo_pgsql, pdo_sqlite, pgsql, phalcon, Phar, posix, pspell, readline, recode, redis, Reflection, session, shmop, SimpleXML, soap, sockets, SPL, sqlite3, standard, sysvmsg, sysvsem, sysvshm, tidy, tokenizer, uploadprogress, wddx, xdebug, xml, xmlreader, xmlrpc, xmlwriter, xsl, Zend OPcache, zip, zlib</p>
</div>


### Email catch-all

<div class="center">
  <img class="battery" title="Email catch-all" alt="Email catch-all" src="/assets/img/logos/64x64/email.png"/>
  <p>The built-in postfix mailserver is configured to automatically intercept all outgoing emails. This is an important measurement during development to make sure not to accidentally send out real emails. Instead you will be able to see all sent emails in the included intranet mail view. See Intranet section below.</p>
</div>


### Auto-DNS

<div class="center">
  <img class="battery" title="Auto-DNS" alt="Auto-DNS" src="/assets/img/logos/64x64/dns.png" />
  <p>Creating a new project just requires you to create a new folder on the filesystem. As you probalby don't want to bother with editing your /etc/hosts file everytime, the built-in DNS server will automatically provide the correct DNS records for every project.</p>
</div>


### Batteries included

<p class="center">No need to download external tools. Everything is bundled, up-to-date and available inside the containers.</p>

<div class="center">
  <a target="_blank" title="phpMyAdmin" href="https://www.phpmyadmin.net"><img class="battery" src="/assets/img/logos/64x64/phpmyadmin.png" alt="Devilbox"/></a>
  <a target="_blank" title="Adminer" href="https://www.adminer.org"><img class="battery" src="/assets/img/logos/64x64/adminer.png" alt="Devilbox"/></a>
  <a target="_blank" title="OpCache GUI" href="https://github.com/amnuts/opcache-gui"><img class="battery" src="/assets/img/logos/64x64/opcachegui.png" alt="Devilbox"/></a> 
  <br/> 
  <a target="_blank" title="Composer" href="https://getcomposer.org"><img class="battery" src="/assets/img/logos/64x64/composer.png" alt="Devilbox"/></a>
  <a target="_blank" title="Drush" href="https://www.drupal.org/project/drush"><img class="battery" src="/assets/img/logos/64x64/drush.png" alt="Devilbox"/></a>
  <a target="_blank" title="Drupal Console" href="https://drupalconsole.com"><img class="battery" src="/assets/img/logos/64x64/drupal-console.png" alt="Devilbox"/></a>
  <a target="_blank" title="NodeJS" href="https://nodejs.org"><img class="battery" src="/assets/img/logos/64x64/nodejs.png" alt="Devilbox"/></a>
  <a target="_blank" title="WP-CLI" href="https://wp-cli.org"><img class="battery" src="/assets/img/logos/64x64/wp-cli.png" alt="Devilbox"/></a>
  <a target="_blank" title="NPM" href="https://www.npmjs.com"><img class="battery" src="/assets/img/logos/64x64/npm.png" alt="Devilbox"/></a>
  <a target="_blank" title="Git" href="https://git-scm.com"><img class="battery" src="/assets/img/logos/64x64/git.png" alt="Devilbox"/></a>
  <a target="_blank" title="mysqldump-secure" href="https://mysqldump-secure.org"><img class="battery" src="/assets/img/logos/64x64/mysqldump-secure.png" alt="Devilbox"/></a>
</div>


### Supported Frameworks and CMS

<p class="center">There is nothing special about the devilbox, so any framework or CMS that will work with normal LAMP/MEAN stacks will work here as well. However in order to make double sure, a few popular applications have been explicitly tested.</p>

<div class="center">
  <a target="_blank" title="CakePHP" href="https://cakephp.org" ><img alt="CakePHP" class="battery" src="/assets/img/logos/64x64/cake.png" /></a>
  <a target="_blank" title="Drupal" href="https://www.drupal.org/" ><img alt="Drupal" class="battery" src="/assets/img/logos/64x64/drupal.png" /></a>
  <a target="_blank" title="Laravel" href="https://laravel.com" ><img alt="Laravel" class="battery" src="/assets/img/logos/64x64/laravel.png" /></a>
  <a target="_blank" title="PhalconPHP" href="https://phalconphp.com" ><img alt="PhalconPHP" class="battery" src="/assets/img/logos/64x64/phalcon.png" /></a>
  <a target="_blank" title="Symfony" href="https://symfony.com" ><img alt="Symfony" class="battery" src="/assets/img/logos/64x64/symfony.png" /></a>
  <a target="_blank" title="Wordpress" href="https://wordpress.org" ><img alt="Wordpress" class="battery" src="/assets/img/logos/64x64/wordpress.png" /></a>
  <a target="_blank" title="Yii" href="http://www.yiiframework.com" ><img alt="Yii" class="battery" src="/assets/img/logos/64x64/yii.png" /></a>
  <a target="_blank" title="Zend Framework" href="https://framework.zend.com" ><img alt="Zend Framework" class="battery" src="/assets/img/logos/64x64/zend.png" /></a>
</div>


### Documentation

<p class="center">If you don't know where to start or just want to see what is possible and how it is done, browse the documentations below. The devilbox is well explained, features many examples and even gives a technical background for customizations.</p>

<div style="text-align:center;">
<div style="width:300px;display;inline-block;text-align:left;margin-left:auto; margin-right:auto; ">
<ol>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md" >Overview</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#1-main-idea" >Main idea</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#2-features" >Features</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#3-supported-host-os" >Supported Host OS</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#4-requirements" >Requirements</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#5-docker-documentation" >Docker documentation</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#6-devilbox-documentation" >Devilbox documentation</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#7-video-tutorials" >Video Tutorials</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#8-available-php-modules" >Available PHP Modules</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/README.md#9-supported-frameworks-and-cms" >Supported Frameworks and CMS</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Quickstart.md" >Quickstart</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Quickstart.md#1-installation" >Installation</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Quickstart.md#2-update" >Update</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Quickstart.md#3-configuration" >Configuration</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Quickstart.md#4-run" >Run</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Quickstart.md#5-project-setup" >Project setup</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Quickstart.md#6-enter-the-php-docker-container" >Enter the PHP Docker container</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Install.md" >Install</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Install.md#1-install-docker" >Install Docker</a>
      <ol>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Install.md#11-linux" >Linux</a></li>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Install.md#12-windows" >Windows</a></li>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Install.md#13-osx" >OSX</a></li>
      </ol>
    </li>
	<li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Install.md#2-install-devilbox" >Install Devilbox</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Update.md" >Update</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Update.md#1-tldr" >TL;DR</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Update.md#2-git-tag-vs-master-branch" >Git tag vs master branch</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Update.md#3-compare-env-file" >Compare .env file</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Update.md#4-pull-new-docker-container-important" >Pull new Docker container (Important!)</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Update.md#5-remove-anonymous-volumes" >Remove anonymous volumes</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Configure.md" >Configure</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Configure.md#1-overview" >Overview</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Configure.md#2-devilbox-general-settings" >Devilbox general settings</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Configure.md#3-project-settings" >Project settings</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Configure.md#4-container-settings" >Container settings</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Configure.md#5-intranet-settings" >Intranet settings</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Configure.md#6-host-computer" >Host computer</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Run.md" >Run</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Run.md#1-start-the-devilbox" >Start the devilbox</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Run.md#2-stop-the-devilbox" >Stop the devilbox</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Run.md#3-attachdetach-during-run-time" >Attach/Detach during run-time</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Run.md#4-docker-logs" >Docker logs</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md" >Usage</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#1-mounted-directories" >Mounted directories</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#2-work-on-the-docker-host" >Work on the Docker host</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#3-work-inside-the-php-container" >Work inside the PHP container</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#4-managing-projects-explained" >Managing Projects explained</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#5-creating-new-projetcs" >Creating new Projects</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#6-switching-container-versions" >Switching container versions</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#7-emails" >Emails</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#8-log-files" >Log files</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Usage.md#9-intranet" >Intranet</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/OS.md" >OS</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/OS.md#1-linux" >Linux</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/OS.md#2-windows" >Windows</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/OS.md#3-osx" >OSX</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md" >Backups</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#1-info" >Info</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#2-mysql" >MySQL</a>
      <ol>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#21-mysql-database-backup" >MySQL Database Backup</a></li>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#22-mysql-database-restore" >MySQL Database Restore</a></li>
      </ol>
    </li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#3-postgresql" >PostgreSQL</a>
      <ol>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#31-postgresql-database-backup" >PostgreSQL Database Backup</a></li>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#32-postgresql-database-restore" >PostgreSQL Database Restore</a></li>
      </ol>
    </li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#4-mongodb" >MongoDB</a>
      <ol>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#41-mongodb-database-backup" >MongoDB Database Backup</a></li>
        <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Backups.md#42-mongodb-database-restore" >MongoDB Database Restore</a></li>
      </ol>
    </li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md" >Examples</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#1-introduction" >Introduction</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#2-setup-cakephp" >Setup CakePHP</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#3-setup-drupal" >Setup Drupal</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#4-setup-laravel" >Setup Laravel</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#5-setup-phalcon" >Setup Phalcon</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#6-setup-symfony" >Setup Symfony</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#7-setup-wordpress" >Setup Wordpress</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#8-setup-yii" >Setup Yii</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Examples.md#9-setup-zend" >Setup Zend</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Technical.md" >Technical</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Technical.md#1-networking" >Networking</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Technical.md#2-ports-and-forwarding" >Ports and forwarding</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Technical.md#3-works-the-same-on-host-and-php-container" >Works the same on Host and PHP Container</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/Hacking.md" >Hacking</a></strong>
  <ol>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Hacking.md#1-rebuilding-bundled-docker-container" >Rebuilding bundled Docker container</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Hacking.md#2-customizing-the-bundled-docker-container" >Customizing the bundled Docker container</a></li>
    <li><a href="https://github.com/cytopia/devilbox/blob/master/docs/Hacking.md#3-adding-your-own-docker-container" >Adding your own Docker container</a></li>
  </ol>
</li>
<li><strong><a href="https://github.com/cytopia/devilbox/blob/master/docs/FAQ.md" >FAQ</a></strong></li>
</ol>
</div>
</div>

### Devilbox Intranet

<p class="center">Once the devilbox is up and running, you can visit the bundled intranet on <a target="_blank" href="http://localhost">http://localhost</a>.<br/>The intranet is not just a simple dash, it provides many useful tools:</p>

<div class="center">
  Container Health | DNS Status | Available vHosts | Emails | Databases | Effective Configuration<br/>
  <img alt="Devilbox Intranet - Virtual Host view" title="Devilbox Intranet - Virtual Host view" src="/assets/img/intranet_02_vhosts.png "/>
  <img alt="Devilbox Intranet - Database view" title="Devilbox Intranet - Database view" src="/assets/img/intranet_03_databases.png "/>
  <img alt="Devilbox Intranet - Email view" title="Devilbox Intranet - Emailview" src="/assets/img/intranet_04_emails.png "/>
</div>


### Security

<p class="center">Be aware that the docker service is running with root privileges on your system (like any other webserver for example). The devilbox is using a mix of official docker images and custom images. All integrated containers are available on <a href="https://github.com/cytopia/devilbox#run-time-matrix">Github</a> and can be reviewed at any time.</p>


### Up-to-dateness

<p class="center">Docker containers are pushed to <a target="_blank" href="https://hub.docker.com/r/cytopia">Docker Hub</a> frequently.<br/>It should be enough for you to pull updated images on a regeular basis.</p>

```shell
$ docker-compose pull
```

<p class="center">However, if a new minor version (PHP for example) has just been released and you want to use it right away, you can simply *git clone* the docker repository and rebuild the container. Each container repository contains a shell script for easy building.</p>

```shell
# Download PHP 7.1 repository
$ git clone https://github.com/cytopia/docker-php-fpm-7.1

# Rebuild the container in order to get the latest minor/patch version
$ cd docker-php-fpm-7.1
$ ./build/docker-rebuild.sh
```


### Integration Tests

<div class="center">
  <a target="_blank" href="https://travis-ci.org/cytopia/devilbox"><img src="https://travis-ci.org/cytopia/devilbox.svg?branch=master" /></a>
</div>

<p class="center">In order to make sure everything always runs stable and as expected, the devilbox makes heavy use of integration tests. You can head over to <a target="_blank" href="https://travis-ci.org/cytopia/devilbox">Travis-CI</a> and have a look at stable and nightly builds.</p>


### Contribute

<div class="center">
  <p>Contributers are welcome in any way.</p>
  
  <p>First of all, if you like the project, please <a href="https://github.com/cytopia/devilbox">do star it</a>. Starring is an important measurement to see the number of active users and better allows me to organize my time and effort I can put into this project.</p>
  
  <p>You can also get actively involved. <a href="https://github.com/cytopia/devilbox">Do clone the project</a> and start improving whatever you think is useful. There is quite a lot todo and planned. If you like to contribute, view <a href="https://github.com/cytopia/devilbox/blob/master/CONTRIBUTING.md">CONTRIBUTING.md</a> and <a href="https://github.com/cytopia/devilbox/issues/23">ROADMAP</a>.</p>
  
  <p>Major contributors will be credited within the intranet and on the github page.</p>
</div>


### License

<div class="center">
  <p>MIT License</p>
  <p>Copyright (c) 2016-2017 cytopia</p>
</div>

