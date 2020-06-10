# Self driving project
This is a project for self driving vehicle which has been trained in google colab using cnn model with tensorflow and keras. 
It has been trained under udacity training mode, collected a data and images and has been trained as a model.h5 file. 
Track that has been used to train our model from udacity is on given link:
https://github.com/Bishworajkdk/track

![](udacity%20image.png)

In order to run the model in the simulator car, we need to create the anaconda environment. 
- conda create --name myenviron
- source activate myenviron
Then, we need to install all the dependencies for web sockets.
- conda install -c anaconda flask
- conda install -c conda-forge eventlet
- conda install -c conda-forge python-socket.io
- conda install -c conda-forge tensorflow 
- conda install -c conda-forge keras 
- conda install -c anaconda pillow
- conda install -c anaconda numpy
- conda install -c conda-forge opencv

Then, we need to run the drive.py file within the myenviron and connect to the local server, then run the simulator in autonomous mode.When the connection is established, the car start driving itself in the autonomous mode.
