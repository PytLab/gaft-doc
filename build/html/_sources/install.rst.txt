Installation
============

Serial version
--------------

If you only want to use GAFT to run some simple mathmetical optimization
without parallel acceleration, you can install GAFT without any
prerequisite.

Via pip (Recommended)
~~~~~~~~~~~~~~~~~~~~~

.. code:: shell

   pip install gaft

From source
~~~~~~~~~~~

.. code:: shell

   git clone --recursive https://github.com/PytLab/gaft.git
   cd gaft
   python setup.py install

Parallel version
----------------

If you want to run your optimization flow in parallel for acceleration,
you need to install an implementation of MPI on your machine and then
mpi4py package.

MPI implementation for different platforms: 1.
`MPICH <https://www.mpich.org/>`__ 2.
`OpenMPI <https://www.open-mpi.org/>`__ 3. `Microsoft
MPI <https://docs.microsoft.com/en-us/message-passing-interface/microsoft-mpi>`__

You also install mpi4py explicitly:

.. code:: python

   pip install mpi4py

Then you can install GAFT in the same way with the serial version.

For developers
--------------

GAFT also provides unit tests for developers, if you have cloned the
repository, just

.. code:: shell

   python setup.py test

or

.. code:: shell

   python -m gaft.tests.test_all
