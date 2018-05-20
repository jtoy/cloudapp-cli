

cloudapp-cli
============

A simple cli for [CloudApp][getcloudapp] written in Ruby.


# This is a working updated version as of May 20,2018!


Install
-------

cloudapp-cli depends on the [cloudapp_api][api], so first install it as a gem dependency:

	gem install cloudapp_api clipboard
	

Install with the one-liner (shock!) (make sure that your /usr/local/bin is writable and it's in PATH):

	cd ~/bin/ && curl -fOs https://raw.github.com/jtoy/cloudapp-cli/master/cloudapp && chmod +x cloudapp && cd -

Usage
-----

Configuration:

	cloudapp config myemail@company.hu passw0rd

List all your drops:

	cloudapp list

Show your stats:

	cloudapp stats

Upload files:

	cloudapp upload drumandbass.ogg cheatsheet.png

Upload a file as private:

	cloudapp upload -p topsecret.pdf

Download a drop to current directory:

	cloudapp download dZ69

Change a drop to private:

	cloudapp private dZ69

Change all drops to public:

	cloudapp public

Rename a drop:

	cloudapp rename dZ69 UserGuide.txt

Delete a drop:

	cloudapp delete dZ69

Recover a drop:

	cloudapp recover dZ69

Jump to your homepage:

	cloudapp home

Enjoy!
------

[getcloudapp]:http://getcloudapp.com/
[api]:https://github.com/aaronrussell/cloudapp_api
