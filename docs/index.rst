
.. toctree::
    :hidden:
    :glob:
    :titlesonly:

    source/code
    source/changelog


A template Python project for scientific software
-------------------------------------------------
For technical questions regarding TEMPLATE usage please contact
`INSERT DEVELOPER <mailto:devel.oper@gmail.com>`_ directly.

Background and Objectives
=========================
This TEMPLATE project serves as a base for building up new scientific software
packages and integrating with automated tools. Specifically, configuration
files are included for the follow tools:

- Pip installation
- TravisCI
- Sphinx
- ReadTheDocs

Citation
========
Add citation info here

.. _installation:

Installation
============
Using ``pip``, TEMPLATE can be installed in two ways

- local editable install

- using a tagged release version from the ``pip`` repo

For consistency between all developers, it is recommended to use Python
virtual environments;
`this link <https://realpython.com/blog/python/python-virtual-environments-a-primer/>`_
provides a great introduction. Using virtual environments in a Jupyter Notebook
is described `here <https://help.pythonanywhere.com/pages/IPythonNotebookVirtualenvs/>`_.

Local Editable Installation
~~~~~~~~~~~~~~~~~~~~~~~~~~~
The local editable installation allows developers to maintain an importable
instance of TEMPLATE while continuing to extend it. The alternative is to
constantly update Python paths within the package to match the local
environment.

Before doing the local install, the source code repository must be cloned
directly from GitHub:

.. code-block:: bash

    git clone https://github.com/rafmudaf/python_template

Then, using the local editable installation is as simple as running the
following command from the parent directory of the
cloned repository:

.. code-block:: bash

    pip install -e template/

Finally, test the installation by starting a python terminal and importing
TEMPLATE:

.. code-block:: bash

    import template

pip Repo Installation
~~~~~~~~~~~~~~~~~~~~~
The TEMPLATE version available through the pip repository is typically the latest
tagged and released major version. This version represents the most recent
stable, tested, and validated code.

In this case, there is no need to download the source code directly. TEMPLATE
and its dependencies can be installed with:

.. code-block:: bash

    pip install template

Dependencies
============
TEMPLATE has dependencies on various math, statistics, and plotting libraries in
addition to other general purpose packages. For the main modules, the
dependencies are listed in ``python_template/requirements.txt``. The
documentation has additional requirements listed in
``python_template/docs/requirements.txt``.

The requirements files can be used to install everything with:

.. code-block:: bash

    pip install -r requirements.txt

License
=======

Copyright 2019 NREL

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
