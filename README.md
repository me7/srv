[![Nimble](https://raw.githubusercontent.com/yglukhov/nimble-tag/master/nimble.png)](https://github.com/me7/srv)

![release](https://img.shields.io/github/release/me7/srv/all.svg)
![license](https://img.shields.io/github/license/me7/srv.svg)

# srv

_srv_ is a static files server that fork from [NimHTTPd](https://github.com/h3rald/nimhttpd).
The reason for fork are
* i want shorter name, srv is shorter than nimhttpd
* this package will default to open http://localhost:1337 after launch

## Usage

**srv** **[** **-p:**_port_ **]** **[** _directory_ **]**

Where:

* _directory_ is the directory to serve (default: current directory).
* _port_ is the port to listen to (default: 1337).