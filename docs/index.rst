.. _home:

mogwai
======

mogwai is an object graph mapper (OGM) designed for Titan Graph Database.

.. image:: https://app.wercker.com/status/767e3cb41d7c6866fd88712bda8fede2/m/master
   :alt: Build Status
   :align: center
   :target: https://app.wercker.com/project/bykey/767e3cb41d7c6866fd88712bda8fede2


NOTE: TinkerPop3 Support
========================
ZEROFAIL has graciously adopted mogwai to grow into a full fledged goblin for TinkerPop3! See more here: https://github.com/ZEROFAIL/goblin

.. _features:

Features
--------

 - Straightforward syntax
 - Query Support
 - Vertex and Edge Support
 - Uses RexPro Connection Pooling
 - Gevent and Eventlet socket support via RexPro
 - Supports Relationship quick-modeling
 - Supports custom gremlin scripts and methods
 - Doesn't restrict the developer from using direct methods.
 - Save Strategies
 - Property Validation
 - Optionally can utilize `factory_boy <http://factoryboy.readthedocs.org/en/latest/>`_ to generate models.
 - Interactive shell available
 - Performance monitoring tools available.
 - Serialization support for Pickle
 - Support for un-modeled properties with dictionary-like access
 - Support for imports via groovy and the groovy Script Engine. (:ref:`See Example <example_groovy_imports>`)
 - Tested with Python 2.7, 3.3 and 3.4


.. _links:

Links
-----

* Documentation: http://mogwai.readthedocs.org/
* Official Repository: https://bitbucket.org/wellaware/mogwai.git
* Package: https://pypi.python.org/pypi/mogwai/

mogwai is known to support Python 2.7, 3.3 and 3.4.


.. _download:

Download
--------

PyPI: https://pypi.python.org/pypi/mogwai/

.. code-block:: sh

    $ pip install mogwai

Source: https://bitbucket.org/wellaware/mogwai.git

.. code-block:: sh

    $ git clone git://bitbucket.org/wellaware/mogwai.git
    $ python setup.py install


Contents
--------

.. toctree::
   :maxdepth: 2

   Home <self>
   quickstart
   internals/index
   examples/index
   changelog
   contribute
   ideas



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

