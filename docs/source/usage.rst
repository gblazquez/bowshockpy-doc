Usage
=====

There are two ways to use bowshockpy, either using a configuration file with the model parameters to be generated or importing bowshockpy as a package and run the model manually.


From a input file
--------------------------

The easiest way to use ``bowshockpy`` is using an input file that contains all the parameters of the model to be generated. You can tell ``bowshockpy`` to read a input file and generate your models either from terminal

.. code-block:: console

   (.venv) $ bowshockpy -r params.py 


Or importing bowshockpy as a package in python

>>> import bowshockpy as bp
>>> bp.generate_bowshock("params.py")

If you want to use an example of an input file, you can print some :doc:`examples`. If you want to print example 1:

  (.venv) $ bowshockpy -p 1

or 

>>> bp.print_example("1")

From a customize script using bowshockpy package
---------------------------------------------

This the most flexible way to use ``bowshockpy``, since you have access to all the classes in the package.

>>> import bowshockpy as bp
