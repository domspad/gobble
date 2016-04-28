These are the most common commands when installing packages

Install package (In the current environment's lib/pythonX.Y/site-packages folder)

	python setup.py install

or
	
	pip install .

"Install" by linking the current folder. Allows continuing developement without
having to reinstall the package each time

	python setup.py develop

Build and "egg" (a specially named zipped file) that can be sent to other people

	python setup.py bdist_egg

The other person installs it with:

	egginst PATH/TO/EGGFILE


You'll find more documentation at "How To Package Your Python Code": http://python-packaging.readthedocs.org/en/latest/