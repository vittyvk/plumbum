1.2
---
* Path: added `chmod <https://github.com/tomerfiliba/plumbum/pull/49>`_
* Path: added `link and symlink <https://github.com/tomerfiliba/plumbum/issues/65>`_
* Path: ``walk()`` now applies filter recursively (`#64 <https://github.com/tomerfiliba/plumbum/issues/64>`_)
* Commands: added `Append redirect <https://github.com/tomerfiliba/plumbum/pull/54>`_
* Commands: fix ``_subprocess`` issue (`#59 <https://github.com/tomerfiliba/plumbum/issues/59>`_)
* Commands: add ``__file__`` to module hack (`#66 <https://github.com/tomerfiliba/plumbum/issues/66>`_)  
* Paramiko: add `'username' and 'password' <https://github.com/tomerfiliba/plumbum/pull/52>`_ 
* Paramiko: add `'timeout' and 'look_for_keys' <https://github.com/tomerfiliba/plumbum/pull/67>`_
* Python 3: fix `#56 <https://github.com/tomerfiliba/plumbum/issues/56>`_ and `#55 <https://github.com/tomerfiliba/plumbum/pull/55>`_

1.1
---
* `Paramiko <http://pypi.python.org/pypi/paramiko/1.8.0>`_ integration 
  `#10 <https://github.com/tomerfiliba/plumbum/issues/10>`_
* CLI: now with built-in support for `sub-commands <http://plumbum.readthedocs.org/en/latest/cli.html#sub-commands>`_.
  See also: `#43 <https://github.com/tomerfiliba/plumbum/issues/43>`_
* The "import hack" has moved to the package's ``__init__.py``, to make it importable directly
  `#45 <https://github.com/tomerfiliba/plumbum/issues/45>`_
* Paths now support ``chmod`` (on POSIX platform) `#49 <https://github.com/tomerfiliba/plumbum/pull/49>`_
* The argument name of a ``SwitchAttr`` can now be given to it (defaults to ``VALUE``) 
  `#46 <https://github.com/tomerfiliba/plumbum/pull/46>`_

1.0.1
-----
* Windows: path are no longer converted to lower-case, but ``__eq__`` and ``__hash__`` operate on
  the lower-cased result `#38 <https://github.com/tomerfiliba/plumbum/issues/38>`_
* Properly handle empty strings in the argument list `#41 <https://github.com/tomerfiliba/plumbum/issues/41>`_
* Relaxed type-checking of ``LocalPath`` and ``RemotePath`` `#35 <https://github.com/tomerfiliba/plumbum/issues/35>`_
* Added ``PuttyMachine`` for Windows users that relies on ``plink`` and ``pscp`` 
  (instead of ``ssh`` and ``scp``) `#37 <https://github.com/tomerfiliba/plumbum/issues/37>`_

1.0.0
-----
* Rename ``cli.CountingAttr`` to ``cli.CountOf``
* Moved to `Travis <http://travis-ci.org/#!/tomerfiliba/plumbum>`_ continuous integration
* Added ``unixutils``
* Added ``chown`` and ``uid``/``gid``
* Lots of fixes and updates to the doc
* Full list of `issues <https://github.com/tomerfiliba/plumbum/issues?labels=V1.0&page=1&state=closed>`_

0.9.0
-----
Initial release
