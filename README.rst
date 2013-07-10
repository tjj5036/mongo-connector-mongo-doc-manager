mongo-connector-elastic-doc-manager
==================================

Mongo Doc Manager for the mongo-connector tool

Usage
-----

Install via::

    python setup.py install

Start the mongo connector with::

    mongo-connector -df mongo_doc_manager    

Alternatively, if you download this module, you can 
start the connector with::

    mongo-connector -d <path_to>/mongo_doc_manager.py

Notes
-----

Previously this was included as part of the mongo-connector package.
The purpose of the separation is to encourage users to install plugins
for mongo-connector with pip as opposed to passing in source files.
However, it is still possible to do that with this module (see usage).
