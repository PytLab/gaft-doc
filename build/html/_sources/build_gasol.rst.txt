Build C++ API
=============

Create dir for build
~~~~~~~~~~~~~~~~~~~~

.. code:: shell

   cd gasol
   mkdir build
   cd build

Build
~~~~~

-  Serial version

.. code:: shell

   cmake ..
   make

-  MPI parallel version

::

   export CXX=/<mpi_path>/mpicxx
   cmake -DMPI=true ..
   make

Run test
~~~~~~~~

.. code:: shell

   make unittest
   ./unittest/unittest
