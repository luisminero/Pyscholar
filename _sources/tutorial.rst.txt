.. _tutorial:

Tutorial
========

Example
-------

The following function performs a search by author.
It receives the first and last name, and returns a list of IDs associated
with the author.

.. code-block:: python

   >>> import pyscholar
   >>> pyscholar.scopus.find_author_scopus_id_by_name("Ruy", "Fabila-Monroy")
   >>> [u'56013555800', u'16635924700']

