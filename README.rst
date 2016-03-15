Sock Js Polymer Component
-------------------------

An element providing a Sock-Js client, wrapped around a sockjs-client_.

Main features:
  - reconnection
  - token authentication


Dependencies
------------

Element dependencies are managed via `Bower <http://bower.io/>`_. You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


Playing With Your Element
-------------------------

If you wish to work on your element in isolation, we recommend that you use
`Polyserve <https://github.com/PolymerLabs/polyserve>`_ to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at `localhost
<http://localhost:8080/components/sock-js/>`_,
where `sock-js` is the name of the directory containing it.


TODO
----

#. Cover all functionality with unittests.
#. Improve demo.



.. _sockjs-client: https://github.com/sockjs/sockjs-client
