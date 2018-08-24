|License| |Issues|

.. _main_title:
************************************************************************
{{cookiecutter.paper_title}}
************************************************************************

**Author**: {{ cookiecutter.author_first_name + ' ' + cookiecutter.author_last_name }} (`{{cookiecutter.author_email}} <mailto:{{cookiecutter.author_email}}>`_)


.. ----------------------------------------------------------------------------

Project based on the `modified <https://github.com/vcalderon2009/https://github.com/vcalderon2009/MNRAS_Cookiecutter>`_


.. |Issues| image:: https://img.shields.io/github/issues/{{cookiecutter.github_project}}.svg
   :target: https://github.com/{{cookiecutter.github_project}}/issues
   :alt: Open Issues

{% if cookiecutter.open_source_license == "BSD 3-Clause" %}
.. |License| image:: https://img.shields.io/badge/License-BSD%203--Clause-blue.svg
   :target: https://github.com/{{cookiecutter.github_project}}/blob/master/LICENSE.rst
   :alt: Project License
{% endif %}

{% if cookiecutter.open_source_license == "GNU GPL v3+" %}
.. |License| image:: https://img.shields.io/badge/license-GNU%20GPL%20v3%2B-blue.svg
   :target: https://github.com/{{cookiecutter.github_project}}/blob/master/LICENSE.rst
   :alt: Project License
{% endif %}

{% if cookiecutter.open_source_license == "Apache Software Licence 2.0" %}
.. |License| image:: https://img.shields.io/badge/license-Apache%20Software%20Licence%202.0-blue.svg
   :target: https://github.com/{{cookiecutter.github_project}}/blob/master/LICENSE.rst
   :alt: Project License
{% endif %}

{% if cookiecutter.open_source_license == "BSD 2-Clause" %}
.. |License| image:: https://img.shields.io/badge/license-BSD%202--Clause-blue.svg
   :target: https://github.com/{{cookiecutter.github_project}}/blob/master/LICENSE.rst
   :alt: Project License
{% endif %}

{% if cookiecutter.open_source_license == "MIT" %}
.. |License| image:: https://img.shields.io/badge/license-MIT-blue.svg
   :target: https://github.com/{{cookiecutter.github_project}}/blob/master/LICENSE.rst
   :alt: Project License
{% endif %}






















