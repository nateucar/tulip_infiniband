# Tulip in a Docker container
Portable Tulip Graphical User Interface

--------------------------------------------------------
# Linux

## Prerequisites:
* gcc
* Docker 

## Build and run Tulip:
```
make
```

## Example: Complete install and run on Ubuntu 18.04 host
* Install gcc
```
sudo apt-get install -y build-essential
```
* Install Docker for Linux
```
sudo apt install -y docker-ce
```
* Build and run Tulip container 
(must be in <...>/tulip_infiniband/contrib/docker)
```
make
```
--------------------------------------------------------
# Macintosh

## Prerequisites:
* gcc
* Docker
* XQuartz

## Build and run Tulip: 
```
make
```

## Example: Complete install and run on macOS 10.12.6 host
* Install gcc
```
xcode-select --install
```
* Install Docker for Mac
```
brew install docker
```
* Install XQuartz
```
brew cask install xquartz
```
* Build and run Tulip container
(must be in <...>/tulip_infiniband/contrib/docker)
```
make
```
--------------------------------------------------------
# Windows not yet supported
