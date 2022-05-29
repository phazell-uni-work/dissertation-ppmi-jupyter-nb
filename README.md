# dissertation-ppmi-jupyter-nb
Code repository for the machine learning experiments of my Masters dissertation project. As an ongoing piece of academic assessment this project is not currently accepting contributions.

## Running the code  

Code is written & run inside a Jupyter Lab environment.  

### _Run in python using pip_
The base directory contains a __requirements.txt__ of pip depenedencies. See pip documentation [here](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/) for details of how to set up an env.  
Once your env is up simply run ```jupyter lab``` on your command line to run the lab (should automatically start your default web browser).  

### _Running in a container_
Dockerfile is in the root directory, if using Docker as your container runtime then you can use the _run_notebook_docker.sh_ script to start the lab. To access the lab you will need the URL & token printed to STDOUT by the startup command so dont run the container as a background process. 
