# ROS over docker

## Clone
`git clone https://github.com/abhijitmajumdar/docker-ros.git`

## Build
`./build`

## Install
`sudo apt install ./docker-ros-deb.deb`

**NOTE**: For a fresh install, the installation pulls down the required docker image(s) and installs default packages to enable functionality, this may take some time

**NOTE**: Once installation is done, resource the current shell (run `source ~/.bashrc`) OR open a new terminal for complete docker-ros functionality

## Use
`docker-ros --help` for help

## Uninstall
`sudo apt remove docker-ros-deb`