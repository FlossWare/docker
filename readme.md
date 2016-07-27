# Docker Functionality

## Docker Image with GUI

This will build a docker image containing a fully functioning FVWM window manager running in a VNC server.  Please note some of the FVMW menu items do not work - this is a work in progress!

Directions to build:
* cd docker/guibase
* docker build -t FlossWare:base .
* cd ../gui
* docker build -t FlossWare:gui .
* docker run -td -p 5901:5901 FlossWare:gui

_The ```vncpassword``` is ```password```_