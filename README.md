# pkg-proj
RPM packaging of PROJ.4 for Sailfish

## Howto build

* Clone this repository with `git clone --recurse-submodules`

* cd into root directory of this repository

* build by running 
```
export SFARCH=armv7hl; mb2 -t SailfishOS-$SFARCH -s rpm/proj.spec build
```
in MER SDK. 

* RPMs are under RPMS directory.
