This is a template Python project
---------------------------------
This project can be used as a starter for future Python projects. It contains
the setup and configuration files for documentation with readthedocs, automated
testing with TravisCI, and installation with pip.

Installation and Package Configuration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
A Python package can be locally "installed" using pip with this command:

.. code-block:: python

    pip install -e <path to package>

requirements.txt
================
List the packages and specific version numbers that you use.




Documentation
~~~~~~~~~~~~~
This template project is configured to produce API documentation as prepared in
docstrings. Docstrings should conform to the
`Google style guide <http://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings>`__
as much as possible.

A `readthedocs <https://readthedocs.org>`__ config file is included at
`python_template/.readthedocs.yml` which contains default settings for a
connection to readthedocs. See the readthedocs `config documentation
<https://docs.readthedocs.io/en/stable/config-file/v2.html>`__ for more details.

Testing
~~~~~~~
All tests should be contained in the `python_template/tests` directory and
reference the module files in `python_template/src`.

A config file for TravisCI is included at `python_template/.travis.yml`.

Things you should modify
~~~~~~~~~~~~~~~~~~~~~~~~
There are some files that will be particular to you project and will need
customization.

.vscode/launch.json
===================
This is the configuration file for debugging in Visual Studio Code. Each
language has a unique syntax for the debugger setup. Included here is the
Python version.

.. code-block:: json

        {
            "name": "test 1",
            "type": "python",
            "request": "launch",
            "stopOnEntry": false,
            "pythonPath": "${config:python.pythonPath}",
            "program": "${workspaceRoot}/examples/example_script.py",
            "cwd": "${workspaceRoot}/examples",
        },


setup.py
========


Things you should NOT modify
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Other files contained in this package 


