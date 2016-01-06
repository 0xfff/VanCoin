VanCoin


A cryptocurrency created for learning and experimental purposes
< based on Litecoin -> BarCoin -> VanCoin>
-SCRYPT
-42 Vancoin per block

TUTORIAL on how to create your own coin based on VanCoin coming soon

vancoin.conf file should be put into your ~/.vancoin directory (on linux)
if you run VanCoin/src/vancoind from terminal it will create the directory for you,
 then it will fail
run VanCoin/src/vancoind stop 
to be sure that it stops
then put vancoin.conf into the ~/.vancoin directory (on linux)
run src/vancoind or vancoin-qt again
it should find and connect to my original node and sync with yours




========================================================================
BUILD:
vancoin-qt is built for linux
src/bitcoind also built for linux

there are makefiles in the src folder for other systems

if you want to build (again) for linux: 
sudo make -f makefile.unix USE_UPNP=-


========================================================================
OPTIONAL:
I would recommend setting up a virtual machine on your system to experiment with VanCoin

I use VirtualBox for a VM
with Ubuntu 14.04

========================================================================
DEPENDENCIES:

once you have ubuntu installed, here are dependencies:

sudo apt-get install build-essential libtool autotools-dev automake pkg-
config libssl-dev libevent-dev bsdmainutils

sudo apt-get install libboost-system-dev libboost-filesystem-dev libboost-
chrono-dev libboost-program-options-dev libboost-test-dev libboost-
thread-dev

sudo apt-get install libboost-all-dev

sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev

apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev
qttools5-dev-tools libprotobuf-dev protobuf-compiler

sudo apt-get install git

sudo apt-get update
========================================================================


OPTIONAL 
========================================================================
DESKTOP:
sudo apt-get install --no-install-recommends lubuntu-desktop
on your VM go to 'Devices' -> 'Insert Guest Additions CD image'
ssh to your VM, run 
sudo /media/<user name>/VboxLinuxAdditions.run
<user name> is the account your created on the VM

there will me more on it in the upcoming tutorial
========================================================================
