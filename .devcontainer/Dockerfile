FROM mcr.microsoft.com/devcontainers/rust:1

RUN sudo apt update -y && sudo apt upgrade -y

RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" && \
unzip awscliv2.zip && \
sudo ./aws/install && \
rm -rf aws awscliv2.zip