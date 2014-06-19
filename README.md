# Personal Vagrant Box

I put this config so that i'm able to set up my development environment on any computer. Even on production servers.

### Usage
1. Install [Virtual Box](https://www.virtualbox.org/wiki/Downloads) and [Vagrant](http://www.vagrantup.com/downloads.html)
2. Make a project directory and cd into it
3. execute `git clone git@github.com:calebdre/Vagrant-Personal-Box.git ./`
4. execute `vagrant up`
5. Check out the php info page at *[localhost:5000](http://localhost:5000)*
6. Start hacking away in the app folder


#### This box includes the following:
### PHP 5
With modules:
- fpm
- cli
- sqlite
- mysql
- mcrypt
- curl

### [Nginx](http://nginx.org/en/)

### [Composer](https://getcomposer.org)

### [NodeJs](https://getcomposer.org/)
With npm modules:
- [Grunt](http://gruntjs.com)

### [Ruby](https://www.ruby-lang.org/en/)
(Version 1.9.3p484)
With gems:
- [Sass](http://sass-lang.com)
- [Compass](http://compass-style.org/)


