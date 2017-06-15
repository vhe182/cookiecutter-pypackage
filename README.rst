======================
Cookiecutter-Cafe : A cookiecutter template for rapidly initializing an OpenCafe working project.
======================

   _ _ _
  ( `   )_
 (    )   `)  _
(____(__.___`)__)
 \ \ \ \ \ \ \ \
  \ \ \ \ \ \ \ \
    ( (
       ) )
    .........
    |       |___
    |       |_  |
    |  >:D  |_| |
    |       |___|
    |_______|


Cookiecutter-Cafe template for an OpenCafe cafe and roast package. Cookiecutter
is originally created by `audreyr`_. This will
generate both repos used for functional test automation. Each repo contains
a directory structure for development.  *This setup is only a guideline, you
are more than welcome to tear out what you do not need*.

.. _`audreyr`: https://github.com/audreyr/cookiecutter-pypackage


* GitHub repo: https://github.com/vhe182/cookiecutter-pypackage/
* Documentation: https://cookiecutter-pypackage.readthedocs.io/
* Free software: BSD license

Features
--------

* Testing setup with ``unittest`` and ``python setup.py test`` or ``py.test``
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3, 3.4, 3.5
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_

.. _Cookiecutter: https://github.com/vhe182/cookiecutter

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/audreyr/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Install the dev requirements into a virtualenv. (``pip install -r requirements_dev.txt``)
* Add the repo to your ReadTheDocs_ account + turn on the ReadTheDocs service hook.
* Release your package by pushing a new tag to master.
* Add a `requirements.txt` file that specifies the packages you will need for
  your project and their versions. For more info see the `pip docs for requirements files`_.

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files

For more details, see the `cookiecutter-pypackage tutorial`_.

.. _`cookiecutter-pypackage tutorial`: https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html
