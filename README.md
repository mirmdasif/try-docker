# try-docker
Example scripts for code school try docker course

# Install Docker
-------------------------

## Step 1 : Remove Older Version
```
sudo apt-get remove docker docker-engine
```
## Step 2 : Recommended extra packages for Trusty 14.04
````
sudo apt-get update

sudo apt-get install \
    linux-image-extra-$(uname -r) \
    linux-image-extra-virtual
````
## Step 3 : Setup Repository

```
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    software-properties-common

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
```
## Step 4 : Install Docker

```
sudo apt-get update
sudo apt-get install docker-ce
```

