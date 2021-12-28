Welcome to {{ cookiecutter.project_name }}'s documentation!
======================================

.. image:: https://img.shields.io/pypi/v/{{ cookiecutter.project_slug }}.svg
        :target: https://pypi.python.org/pypi/{{ cookiecutter.project_slug }}

.. image:: https://img.shields.io/travis/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg
        :target: https://travis-ci.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}

.. image:: https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/docs.yml/badge.svg
        :target: https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/docs.yml
        :alt: Documentation Status

.. image:: https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/python-package.yml/badge.svg
        :target: https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/python-package.yml
        :alt: Python package


.. toctree::
   :maxdepth: 1
   :caption: Contents:

   info
   installation
   getting_started
   api
   contributing
   license
   {% if cookiecutter.create_author_file == 'y' -%}authors
   {% endif -%}
   changelog

Indices and tables
==================
* :ref:`genindex`
* :ref:`modindex`
