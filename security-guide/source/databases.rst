=========
Databases
=========

The choice of database server is an important consideration in the
security of an OpenStack deployment. Multiple factors should be
considered when deciding on a database server, however for the scope of
this book only security considerations will be discussed. OpenStack
supports a variety of database types. See the `OpenStack Administrator
Guide <https://docs.openstack.org/admin-guide/>`_ for more
information.

The Security Guide currently focuses on PostgreSQL and MySQL.

.. toctree::
   :maxdepth: 2

   databases/database-backend-considerations.rst
   databases/database-access-control.rst
   databases/database-transport-security.rst
.. case-studies/database-case-studies.rst
