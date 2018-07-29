# RFID Reader Configuration Instructions

This document details the steps taken to configure the RFID reader portion of our room monitor devices.

## Install RFID Drivers and API

The devices we are using are provided by ThingMagic and use their "MercuryAPI". The installation/configuration is fairly straight forward and is described as follows:

The details on this package and further instructions are located on [GitHub](https://github.com/gotthardp/python-mercuryapi)

Install some pre-requisities

```bash
# Install some pre-reqs
sudo apt install patch xsltproc gcc libreadline-dev python3-dev -y

# clone the wrapper repository
git clone https://github.com/gotthardp/python-mercuryapi.git

# download/build the Mercury API
cd python-mercuryapi
make

```

