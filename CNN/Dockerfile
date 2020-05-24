# Tensorflow docker image for tensorflow environment
FROM tensorflow/tensorflow

# Maintainer
MAINTAINER kaushal soni <kaushal95300@gmail.com>

# For Inital update
RUN apt-get update

# for sudo or root access
RUN apt-get install sudo 

# pip update
RUN python3 -m pip install --upgrade pip

# Basic CNN packages
RUN sudo pip3 install keras numpy pillow scikit-learn pandas joblib  
