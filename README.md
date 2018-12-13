proxy.py
========

Lightweight HTTP, HTTPS and WebSockets Proxy Server in Python.

Features
--------

- Distributed as a single file module
- No external dependency other than standard Python library
- Support for `http`, `https` and `websockets` request proxy
- Basic authentication support

Install
-------

To install proxy.py, simply:

	$ pip install proxy.py

Usage
-----

```
$ proxy.py -h
usage: proxy.py [-h] [--hostname HOSTNAME] [--port PORT] [--backlog BACKLOG]
                [--basic-auth BASIC_AUTH] [--log-level LOG_LEVEL]

proxy.py v0.3

optional arguments:
  -h, --help            show this help message and exit
  --hostname HOSTNAME   Default: 127.0.0.1
  --port PORT           Default: 8899
  --backlog BACKLOG     Default: 100. Maximum number of pending connections to
                        proxy server
  --basic-auth BASIC_AUTH
                        Default: No authentication. Specify colon separated
                        user:password to enable basic authentication.
  --log-level LOG_LEVEL
                        DEBUG, INFO (default), WARNING, ERROR, CRITICAL

Having difficulty using proxy.py? Report at:
https://github.com/abhinavsingh/proxy.py/issues/new
```
