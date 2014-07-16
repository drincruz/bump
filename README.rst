bump
====

.. image:: http://img.shields.io/pypi/v/bump.png

Bumps package versions

Usage:
------

Bump patch version ::

    $ bump setup.py
    1.0.2 => 1.0.3
    Is this ok? y/n y
    Updated setup.py

Bump minor version ::

    $ bump setup.py -m
    1.0.3 => 1.1.0
    Is this ok? y/n y
    Updated setup.py

Bump major version ::

    $ bump setup.py -M
    1.1.0 => 2.0.0
    Is this ok? y/n y
    Updated setup.py

Add suffix ::
    
    $ bump setup.py -M -s=-rc
    2.0.0 => 3.0.0-rc
    Is this ok? y/n y
    Updated setup.py

Bump suffix version ::

    $ bump setup.py -s=-rc -S
    1.1.0-rc.1 => 1.1.0-rc.2
    Is this ok? y/n y
    Updated setup.py

Quiet mode ::

    $ bump setup.py -q
    3.0.1-rc
