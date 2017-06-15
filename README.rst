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


Cookiecutter_ template for an OpenCafe cafe and roast package. Cookiecutter
is originally created by audreyr:
    https://github.com/audreyr/cookiecutter-pypackage

Cookiecutter-Cafe generates both repos used for functional test automation. Each repo
contains a directory structure for development.  *This setup is only a
guideline, you are more than welcome to tear out what you do not need or add
anything you want*.

* GitHub repo: https://github.com/vhe182/cookiecutter-pypackage/
* Documentation: https://cookiecutter-pypackage.readthedocs.io/
* Free software: BSD license

Features
--------

* Testing setup with ``unittest`` and ``python setup.py test`` or ``py.test``
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3, 3.4, 3.5
* Sphinx_ docs: Documentation ready for generation with, for example, GitHubPages_
* Bumpversion_: Pre-configured version bumping with a single command

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _OpenCAFE: https://github.com/CafeHub/opencafe

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

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files


.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _GitHubPages_: https://pages.github.com/
.. _Bumpversion: https://github.com/peritus/bumpversion
