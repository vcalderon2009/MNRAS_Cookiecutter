|RTD| |License| |Issues|

.. _INSTALL_MAIN:

************************************************************************
Downloading and Creating your own Paper
************************************************************************

**Author**: `Victor Calderon <http://vcalderon.me>`_ (`victor.calderon@vanderbilt.edu <mailto:victor.calderon@vanderbilt.edu>`_)

**Description**: An easy, reasonably standardized, but flexible template for creating paper for
the `Monthly Notices of the Royal Astronomical society <https://academic.oup.com/mnras>`_

.. _install_requirements:

============================================
Requirements to use `cookiecutter` templates
============================================

The minimum rquirements for creating `cookiecutter` templates are:

- Python 2.7 or 3.5
- `Cookiecutter Python package <http://cookiecutter.readthedocs.org/en/latest/installation.html>`_ >= 1.4.0: This can be installed with `pip` or `conda` depending on how you manage your Python packages.

You  can install it by typing this on the terminal

.. code-block:: bash

    pip install cookiecutter

or via Anaconda:

.. code-block:: bash

    conda config --add channels conda-forge
    conda install cookiecutter

Now you can use `cookiecutter` to create new templates for projects and papers!

.. _creating_new_paper:

=====================
Creating a new Paper
=====================

After having done the steps in :ref:`install_requirements`, you can start
creating the skeleton for the new MNRAS paper.

To start a new paper, run:

.. code-block:: bash

    cookiecutter https://github.com/vcalderon2009/MNRAS_Cookiecutter

This will prompt you to answer a few questions like:

Next, it will prompt you for some answers.
The different prompts are:

+----------------------------+--------------------------------------------------------------------------+
|Question                    | Description                                                              |
+============================+==========================================================================+
|:code:`author_first_name`   | Author's first name. :code:`author_first_name` will used                 |
|                            | for the *title page* of the paper.                                       |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * Adam                                                                   |
|                            | * Rose                                                                   |
+----------------------------+--------------------------------------------------------------------------+
|:code:`author_last_name`    | Author's **last** name. :code:`last_name` will used for the *title page* |
|                            | of the paper.                                                            |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * Calderon                                                               |
|                            | * Piscionere                                                             |
+----------------------------+--------------------------------------------------------------------------+
|:code:`author_name`         | Author's first name. :code:`author_name` will used                       |
|                            | for the *title page* of the paper.                                       |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * Adam Sanchez                                                           |
|                            | * Rose Roserberg                                                         |
+----------------------------+--------------------------------------------------------------------------+
|:code:`author_email`        | Author's first name. :code:`author_email` will used                      |
|                            | for the *title page* of the paper.                                       |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * some_email@gmail.com                                                   |
|                            | * another_email@yahoo.com                                                |
+----------------------------+--------------------------------------------------------------------------+
|:code:`author_affiliation`  | Name of the department. Default: **Physics and Astronomy**.              |
|                            | Should **not** contain '_' (underscores) symbols.                        |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * Vanderbilt University                                                  |
|                            | * Some other University                                                  |
+----------------------------+--------------------------------------------------------------------------+
|:code:`paper_title`         | Title of the thesis. Should not have '_' symbols in                      |
|                            | it.                                                                      |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * Understanding Exoplanets and Other Variable Sources                    |
|                            | * The Clustering of Galaxies on the Smallest Scales                      |
|                            |   Across Cosmic Time                                                     |
+----------------------------+--------------------------------------------------------------------------+
|:code:`paper_pubyear`       | Year of the current publication. Must be numeric.                        |
|                            |                                                                          |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * Understanding Exoplanets and Other Variable Sources                    |
|                            | * The Clustering of Galaxies on the Smallest Scales                      |
|                            |   Across Cosmic Time                                                     |
+----------------------------+--------------------------------------------------------------------------+
|:code:`repo_name`           | Name of the directory/repository, in which the thesis will be saved.<br> |
|                            | This name is selected by default, but can be changed.<br>                |
|                            | This field **should not contain spaces**.                                |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * Calderon_Victor_Astro_PhD_Thesis                                       |
|                            | * Szewciw_Adam_Astro_PhD_Thesis                                          |
+----------------------------+--------------------------------------------------------------------------+
|:code:`github_username`     | Author's Github username. This will be use to link to the paper          |
|                            | Github repository.                                                       |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * username                                                               |
|                            | * username2018                                                           |
+----------------------------+--------------------------------------------------------------------------+
|:code:`github_project`      | Name of the project on Github                                            |
|                            |                                                                          |
|                            | Examples:                                                                |
|                            |                                                                          |
|                            | * Awesome_Paper_username_2018                                            |
|                            | * Another_awesome_paper                                                  |
+----------------------------+--------------------------------------------------------------------------+
|:code:`open_source_license` | Type of License for the paper. Without this, one cannot use any of       |
|                            | This material.                                                           |
|                            |                                                                          |
|                            | Options:                                                                 |
|                            |                                                                          |
|                            | * MIT                                                                    |
|                            | * BSD 3-Clause                                                           |
|                            | * GNU GPL v3+                                                            |
|                            | * Apache Software Licence 2.0                                            |
|                            | * BSD 2-Clause                                                           |
+----------------------------+--------------------------------------------------------------------------+

.. _using_template:

=====================
Using the Template
=====================

Now that one has answered the questions from :ref:`creating_new_paper`,
you just need to fill in the documents in the ``Section_files`` directory
according to your project's needs.

The structure of the finalized project can be found in the
:ref:`proj_structure` section.


.. ----------------------------------------------------------------------------

Project based on the `modified <https://github.com/vcalderon2009/MNRAS_Cookiecutter>`_  version of the
`MNRAS LaTeX Template <https://www.overleaf.com/latex/templates/monthly-notices-of-the-royal-astronomical-society-mnras-latex-template-and-guide-for-authors/kqnjzrwjwjth>`_.

.. |Issues| image:: https://img.shields.io/github/issues/vcalderon2009/MNRAS_Cookiecutter.svg
   :target: https://github.com/vcalderon2009/MNRAS_Cookiecutter/issues
   :alt: Open Issues

.. |RTD| image:: https://readthedocs.org/projects/mnras-cookiecutter/badge/?version=latest
   :target: https://mnras-cookiecutter.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status

.. |License| image:: https://img.shields.io/badge/license-MIT-blue.svg
   :target: https://github.com/vcalderon2009/MNRAS_Cookiecutter/blob/master/LICENSE
   :alt: Project License
