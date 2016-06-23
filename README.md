# Deep Learning from Scratch

This course is organized by the Data Science Group @ UB

Deep learning is one of the fastest growing areas of machine learning and a hot topic in both academia and industry.
This course will cover the basics of deep learning by using a hands-on approach.

## Course Agenda

<li> Introduction to Deep Learning and its applications. Using the Jupyter notebook & Docker.
<li> Basic Concepts: Score & Loss functions, Optimization (SGD), Linear Regression.
<li> Automated differentiation, Backpropagation, Training a Neural Netwotk from Scratch.
<li> Tensorflow programming model. 
<li> Convolutions & CNN models.
<li> Recurrent Neural Netwoks.
<li> Unsupervised Learning.
<li> Advanced Applications: Neural art, colorization, music generation.

## Course Software Installation

There’s full documentation on installing Docker at ``docker.com``, but in a few words, the steps are:

+ Go to ``docs.docker.com`` in your browser.
+ Step one of the instructions sends you to download the Docker Toolbox.
+ On the Toolbox page, click on the Mac/Windows download button.
+ Run that downloaded file to install the Toolbox.
+ At the end of the install process, chose the Docker Quickstart Terminal.
+ This opens up a new terminal window that runs through an installation script.
+ At the end of the script, you will see ASCII art of a whale and your are left at a prompt.
+ Run this command in the terminal: ``docker run hello-world``
+ This will give you output confirming your installation of docker has worked: ``Hello from Docker``
+ In the docker terminal, run (This operation requires a good internet connection to download ~2.5Gb; it will take some minutes):  ``docker pull deepub/deepub``    
+ Run the DeepUB image on your system: ``docker run -i -t -p 8888:8888 deepub/deepub``
+ Once these steps have been done, you can check the installation by starting your web browser and introducing this  URL: ``http://localhost:8888`` (or ``http://<DOCKER-MACHINE-IP>:8888`` if you are using a Docker Machine VM) to access to the fully operational Jupyter notebook of this course. (Note: the address of your Docker Machine VM is printed at the end of the Docker booting process, just after the ASCII whale).
