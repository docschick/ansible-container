Installation
============

.. contents:: Topics

.. _getting_ansible_container:

Getting Ansible Container
`````````````````````````

Since we are pre-release, the best option for obtaining Ansible Container is to run from source.

.. _running_from_source:

Running from Source
```````````````````
First, you need python 2.7 and `git <https://git-scm.com/book/en/v2/Getting-Started-Installing-Git>`_. You 
also need access to a Docker daemon, which may require installing Docker or Docker Machine.

Clone the repo:

.. code-block:: bash

    $ git clone git@github.com:ansible/ansible-container.git

Install prerequisites using the requirements file in your local ansible-container repo:

.. code-block:: bash

    $ cd ansible-container
    $ pip install -r requirements.txt

Build and install ansible-container:

.. code-block:: bash

    $ python ./setup.py build
    $ python ./setup.py install









