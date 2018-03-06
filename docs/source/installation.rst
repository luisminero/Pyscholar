.. _installation:

Installation
============

Requirements
------------

Pyscholar is required to have the following packages installed:

* `Python 2 <https://docs.python.org/2/using/index.html>`_ >= 2.7.x.
  It can be installed on Debian-based systems with:

  .. code-block:: console

     apt install python

* `pip <https://pip.pypa.io/en/stable/installing/>`_ can also be installed in Debian-based systems with:

  .. code-block:: console

     apt install python-pip

After installing both Python and pip, the dependencies can be easily installed.
   
* `NetworkX <https://networkx.github.io/documentation/>`_

  .. code-block:: console

     pip install networkx

* `Matplotlib <https://matplotlib.org/users/installing.html>`_

  .. code-block:: console

     pip install matplotlib

* `Pandas <http://pandas.pydata.org/pandas-docs/stable/install.html>`_

  .. code-block:: console

     pip install pandas

.. note:: You will need admin permissions to install system-wide.
.. warning:: Pyscholar does not support Python 3.

Step-by-Step Installation Guide
-------------------------------

Before installing Pyscholar you must get your API Key from the following `link <http://dev.elsevier.com/myapikey.html>`_.

Once you have an API key we can continue with the installation of Pyscholar.

1. Clone the repository first as follows:

   .. code-block:: console

      $ git clone https://github.com/rfabila/Pyscholar.git

2. Navigate to the installation directory from the command line, if cloned in home directory:

   .. code-block:: console

      $ cd ~/Pyscholar      

3. Then you must run setup.py and enter your API key:

   .. code-block:: console

      $ python setup.py
      $ Your Scopus API key: (Here you enter your API key)

4.  Finally we can check the installation by doing the following:
   
    * Execute a Python `REPL <https://en.wikipedia.org/wiki/REPL>`_
      with the :command:`python` or :command:`ipython` commands, for example:

      .. code-block:: console

	 $ python
	 Python 2.7.6 (default, Jun 22 2015, 17:58:13) 
	 [GCC 4.8.2] on linux2
	 Type "help", "copyright", "credits" or "license" for more information.
	 >>>
	 
    * Now we just need to import the package:

      .. code-block:: python

	 >>> import pyscholar

If ``import pyscholar`` didn't fail, then the installation was successful.

