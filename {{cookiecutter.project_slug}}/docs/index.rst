Welcome to {{ cookiecutter.project_name }}'s documentation!
======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   installation
   usage
   modules
   {% if cookiecutter.create_author_file == 'y' -%}authors
   {% endif -%}Release history <changes>

Indices and tables
==================
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
