# pickleDB
Fork of [PickleDB](https://bitbucket.org/patx/pickledb) with support for Python 3 and UTF-8.
Compatible Python >= 2.6 and 3.

#### Original README

pickleDB is lightweight, fast, and simple database based on Python's own 
json module. And it's BSD licensed!


##### pickleDB is Fun

    >>> import pickledb

    >>> db = pickledb.load('test.db', False)

    >>> db.set('key', 'value')

    >>> db.get('key')
    'value'

    >>> db.dump()
    True

##### Links

* [website](http://packages.python.org/pickleDB/)
* [documentation](http://packages.python.org/pickleDB/commands.html)
* [pypi](http://pypi.python.org/pypi/pickleDB)
