Introduction
============

FilterPype is being used for multi-level data analysis, but could be applied to 
many other areas where it is difficult to split up a system into small 
independent parts.

Some of its features:

* Advanced algorithms broken down into simple data filter coroutines
* Pipelines constructed from filters in the new FilterPype mini-language
* Domain experts assemble pipelines with no Python knowledge required
* Sub-pipelines and filters linked by automatic pipeline construction
* All standard operations available: branching, joining and looping
* Recursive coroutine pipes allowing calculation of e.g. factorials
* Using it is like writing a synchronous multi-threaded program

Project sponsored by `Flight Data Services`_ and released under the Open 
Software License (`OSL-3.0`_).

Installation
------------

Package requires ``pip`` for installation.
::

    pip install FilterPype

Source Code
-----------

Source code is available from `GitHub`_:

* https://github.com/FlightDataServices/FilterPype

Documentation
-------------

Documentation is available from the `Python Package Index`_:

* http://packages.python.org/FilterPype/

.. _Flight Data Services: http://www.flightdataservices.com/
.. _OSL-3.0: http://www.opensource.org/licenses/osl-3.0.php
.. _GitHub: https://github.com/
.. _Python Package Index: http://pypi.python.org/

.. image:: https://cruel-carlota.pagodabox.com/3ac79d67e6ef73f583c5856ee8942cef
    :alt: githalytics.com
    :target: http://githalytics.com/FlightDataServices/FilterPype
