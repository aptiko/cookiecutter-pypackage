{{ cookiecutter.project_name }} documentation
=============================================

.. toctree::
   :maxdepth: 1
   :caption: Contents:

   quick-start
   api
   {% if cookiecutter.create_author_file == 'y' -%}authors
   {% endif -%}Release history <changes>

Indices and tables
==================
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
