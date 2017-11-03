---
layout: page
title: Get Started
permalink: /getstarted/
---

## Installation

Let's get down to business!

- Via [Vagrant](https://www.vagrantup.com)

```
git clone https://github.com/unicornsnek/unicornsnek.git
cd unicornsnek
vagrant up
```

Then visit [`http://localhost:8000`](http://localhost:8000) in your browser.

- Via [LXC](https://linuxcontainers.org)

```
curl https://raw.githubusercontent.com/unicornsnek/unicornsnek/master/lxc.sh | bash
```

Then visit [`http://localhost:8000`](http://localhost:8000) in your browser.

- Via [Composer](https://getcomposer.org)

```
git clone https://github.com/unicornsnek/unicornsnek.git
cd unicornsnek
composer install
```

You can now run a PHP 7 web server with `public/` as document root.

To get started, fire up PHP's built-in development server

```
php -S localhost:4000 -t public
```

then visit [`http://localhost:4000`](http://localhost:4000) in your browser.
