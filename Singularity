Bootstrap: docker
From: ubuntu:latest

%runscript
    echo "This is what happens when you run the container..."

%post
    echo "Hello from inside the container"
    apt-get update
    apt-get -y install vim
    apt-get -y install python3.6
    apt -y update
    apt -y install python3-pip
apt-get clean
