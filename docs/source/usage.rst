Usage
=====

There are two ways to use bowshockpy, either using a configuration file with the model parameters to be generated or importing bowshockpy as a package and run the model manually.


From a configuration file
--------------------------

The easiest way to use **bowshockpy** is using configuration file that contains all the parameters of the model to be generated. You can tell **bowshockpy** to read a configuration file and generate your models either from terminal

.. code-block:: console

   (.venv) $ python generate_bowshock.py 


Or importing bowshockpy as a package in python

>>> import bowshockpy as bp
>>> bp.generate_bowshock("bowshock_params.py")


From a customize script using bowshockpy package
---------------------------------------------

This the most flexible way to use **bowshockpy**, since you have access to all the classes in the package.

>>> import bowshockpy as bp
