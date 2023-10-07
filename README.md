# BioEngine

# Preparation on the Jetson

```bash
# step 1, install Python PIP
$ sudo apt-get update -y
$ sudo apt-get install python3-pip

# step 2, install Docker Compose build dependencies for Ubuntu 18.04 on aarch64
$ sudo apt-get install -y libffi-dev libssl-dev python-openssl

# step 3, install latest Docker Compose via pip
$ sudo -H pip3 install docker-compose
```

## Usage
### Start the BioEngine Locally
 * Download docker
 * Change the configuration (password, tokens etc.) in the .env file
 * Run `sudo docker compose up`

