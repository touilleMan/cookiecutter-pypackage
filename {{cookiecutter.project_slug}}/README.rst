===============================
{{ cookiecutter.project_name }}
===============================

.. image:: https://img.shields.io/pypi/v/{{ cookiecutter.project_slug }}.svg
        :target: https://pypi.python.org/pypi/{{ cookiecutter.project_slug }}

.. image:: https://img.shields.io/travis/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg
        :target: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}

.. image:: https://readthedocs.org/projects/{{ cookiecutter.project_slug }}/badge/?version=latest
        :target: https://readthedocs.org/projects/{{ cookiecutter.project_slug }}/?badge=latest
        :alt: Documentation Status
{% if cookiecutter.use_coveralls == 'y' -%}

.. image:: https://coveralls.io/repos/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/badge.svg?branch=master
    :target: https://coveralls.io/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
    :alt: Code coverage
{%- endif %}

{{ cookiecutter.project_short_description}}

* Free software: MIT license
* Documentation: https://{{ cookiecutter.project_slug }}.readthedocs.org.

Features
--------

* TODO

Credits
---------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
