# tank-c - tank simulator

## C implementation of a Uniquid node

tank-c is an application that demonstarte the Uniquid Identity and Access Management sdk using the uidcore-c library.

It builds on generic Linux

It requires:

* libcurl
* libpthread
* uidcore-c
* libpaho-mqtt

## download
clone with --recurse-submodules:<br>
git clone --recurse-submodules git@github.com:uniquid/tank-c.git<br>
cd tank-c
## build the project:
make
## run
cd bin<br>
./tank-c
