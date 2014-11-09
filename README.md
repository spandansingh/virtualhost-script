# VirtualHost Script

VirtualHost Script is a bash script by which you can create virtualhost for Linux (Debian/Ubuntu) Platform.

### Features

* Create virtual host hassle free just by giving the address of document root. 
* List all the virtual host at once.
* Delete virtual host easily.

## Installing

_[Manual]_

* Download this: [https://github.com/spandansingh/virtualhost-script//zipball/master](https://github.com/spandansingh/virtualhost-script//zipball/master)
* Unzip that download.

_[GIT Clone]_

	git clone git://github.com/spandansingh/virtualhost-script.git

Copy the `virtualhost` to `/usr/local/bin` to make the command work globally.
## Documentation

	1) sudo virtualhost create <hostname> <document root>
	eg: sudo virtualhost create abc.local ~/websites/abc
	
	2) sudo virtualhost list 
	
	3) sudo virtualhost delete <hostname>
	eg: sudo virtualhost create abc.local

That's it. Enjoy !

