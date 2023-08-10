FROM mcr.microsoft.com/devcontainers/python:3

RUN sudo apt update -y && sudo apt upgrade -y
# Install python development libraries
RUN sudo apt install -y python3-dev python3-setuptools
# Install prerequisite libraries for Pillow
RUN sudo apt install -y libtiff5-dev \
    libjpeg62-turbo \
    libopenjp2-7-dev \
    zlib1g-dev \
    libfreetype6-dev \
    liblcms2-dev \
    libwebp-dev \
    tcl8.6-dev \
    tk8.6-dev \
    python3-tk \
    libharfbuzz-dev \
    libfribidi-dev \
    libxcb1-dev
# Install AWS-CLI
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-aarch64.zip" -o "awscliv2.zip" \
    && unzip awscliv2.zip \
    && sudo ./aws/install \
    && rm -rf ./aws/install awscliv2.zip