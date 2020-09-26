============
Json Checker
============

- STATUS: FINISHED.


Check the python dict type via json file.


Usage
-----

.. code-block:: python

    from json_checker import json_checker
    is_equal, msg = json_checker.check_from_file('example.json', {"a": 1, "b": 2})


