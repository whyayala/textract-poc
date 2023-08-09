FROM mcr.microsoft.com/devcontainers/python:3

RUN sudo apt update -y && sudo apt upgrade -y
# Install python development libraries
RUN sudo apt install -y python3-dev python3-setuptools
# Install prerequisite libraries for Pillow
RUN sudo apt install libtiff5-dev libjpeg8-dev libopenjp2-7-dev zlib1g-dev \
    libfreetype6-dev liblcms2-dev libwebp-dev tcl8.6-dev tk8.6-dev python3-tk \
    libharfbuzz-dev libfribidi-dev libxcb1-dev