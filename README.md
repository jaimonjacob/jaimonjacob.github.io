# This is a sample course created using Adapt Authoring tool.The following are the install instructions for Ubuntu 14.04 LTS.

## Linux upgrade

```
sudo apt-get update
sudo apt-get upgrade

```

## Mongodb

```
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv EA312927
echo "deb http://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.2.list
sudo apt-get update
sudo apt-get install -y mongodb-org
sudo service mongod start

```

## Git

```
sudo apt-get install git
git config --global user.name "username"
git config --global user.email "e-mail"

```
## Node.js


```
$ sudo apt-get install python-software-properties
$ curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
$ sudo apt-get install nodejs
node --version
npm --version

```
## FFMPEG

```
sudo add-apt-repository ppa:mc3man/trusty-media  
sudo apt-get update  
sudo apt-get install ffmpeg  
sudo apt-get install frei0r-plugins  

```
## Grunt CLI

```
sudo npm install -g grunt-cli
grunt --version

```
## Adapt dependencies

```
sudo apt-get install libssl-dev

sudo add-apt-repository ppa:ubuntu-toolchain-r/test 
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade

```
## Adapt CLI

```
sudo npm install -g adapt-cli
adapt --version

```
## Final installation

```
git clone https://github.com/adaptlearning/adapt_authoring.git
cd adapt_authoring
sudo npm install --production
sudo node install
sudo node server

```
