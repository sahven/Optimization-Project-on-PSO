# particle swarm optimizer 


###this is a simple implementation of a particle swarm optimizer in c++, and it's visualization using matplotlib

particles are implemented as a vector of objects.
The optimize() function outputs the position of each particle on every iteration (separated by a tab), which is piped to the plotting.py file.

Set the functions in the function call to optimize() and also in the plotting.py( to get the contour plot of the objective function in the background)
The blue lines represent particles
The green line represents group best position


# Required Packages
1. tkinter - Needed to install via your system's package manager (package name : python3-tkinter)
			 e.g. For Ubuntu : sudo apt install python3-tkinter

### The following packages should be installed through pip3
1. numpy
2. matplotlib
3. scipy


# How to run:
1. First compile pso_impl.cpp through g++ compiler. e.g. g++ pso_impl.cpp -o pso_impl.out
2. Pipe the output of above generated file to plotting.py by using the command : 
	./pso_impl.out | python3 plotting.py