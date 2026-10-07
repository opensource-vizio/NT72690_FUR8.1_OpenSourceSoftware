# NT72690\_FUR8.1\_OpenSourceSoftware

## Identifiers
|Item|Value
|---|---
|Chipset|NT72690
|Release|FUR8.1
|FW Versions|90.810.X.Y
|Download Link|https://d2mi77xcznxniv.cloudfront.net/index.html?file=NT72690_FUR8.1.tar.gz

## Environment
Individual build components may list different versions of Ubuntu for compilation in their respective README or build instruction files.
However, all components were compiled successfully on Ubuntu 22.04 (jammy).

### Preparing your Ubuntu environment
Run the following commands:
```
sudo apt-get update
sudo apt-get install build-essential docker.io docker-buildx 
```

You may also want to add your user to the docker group (`adduser <username> docker`), and log out
and back in. This will remove the need to run docker commands via sudo.

### Build System Specs
The Novatek kernel requires a large amount of RAM (~64GB) to successfully compile. It also takes
up a lot of disk space, so ~150GB is recommended for a full build of this tarball.

## Build Instructions 
After downloading the tarball, run the following commands:
```
tar xzf NT72690_FUR8.1.tar.gz 
cd NT72690_FUR8.1
./build.sh all
```

Further instructions for the contents of the tarball can be found in its included README.

Download the source archive here: 
https://d2mi77xcznxniv.cloudfront.net/index.html?file=NT72690_FUR8.1.tar.gz

