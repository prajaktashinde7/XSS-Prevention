AUTHORS: 

PRAJAKTA SHINDE AND 
SHIBANI SINGH 

Description:


There are 4 steps involved in the execution of Polaris.


1. For the installation of the required packages, run the following commands in the unzipped "Polaris" folder:

	
	python setup.py build

	
	python setup.py install


2. Open clean.php and change the path of the HTMLPurifier, according to the path in your system.


3. To create the executable "polaris", run the command: 
	
	
	make




4. Now to execute polaris, run the command in the following format:


	./polaris <path of input file> <path of output file>


