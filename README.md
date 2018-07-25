GoodServer
=================================
Yet another web server.

GoodServer is a good web server that designed from groud up to support new idea and make
engineering looks elegant and easy. The web server is designed to use coroutine internally
to handle each connection. The coroutine is a asymetric stackful coroutine implementaiton
in C , via library cro. Additionally, other experimental features are utilized as well.

The web server is designed to support millions of virtual isolated user internally, ie CDN
usage.
