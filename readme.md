# ROS over docker
User-friendly ROS functionality over docker

## Install
```bash
curl -s --compressed "https://abhijitmajumdar.github.io/ppa/ubuntu/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/abhijitmajumdar.list "https://abhijitmajumdar.github.io/ppa/ubuntu/abhijitmajumdar.list"
sudo apt update
sudo apt install docker-ros-deb
```

**NOTE**: For a fresh install, the installation pulls down the required docker image(s) and installs default packages to enable functionality, this may take some time

**NOTE**: Once installation is done, re-source the current shell (run `source ~/.bashrc`) OR open a new terminal for complete docker-ros functionality

## Use
`docker-ros --help` for help

## Uninstall
`sudo apt remove docker-ros-deb`
