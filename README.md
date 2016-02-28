# CGIServer 1

Serve CGI scripts.

## Install

Run install script.

	#  ./install.sh

## Use

You may run the cgiserver combined with tcpserver.

	$ tcpserver 0.0.0.0 8000 cgiserver --dir /srv/www

The directory must exist and contain cgiscripts.
While server is running, you can call your scripts from browser.
