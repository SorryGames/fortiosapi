# fortiosapi


### Introduction
> Forked from [official fortiosapi repository](https://github.com/fortinet-solutions-cse/fortiosapi). 
This repository contains fixed SSH method for FortiGate devices.

The official repository has implemented SSH method that has a bug (connection can be closed before all output from the device was read). 


The fact that the official repository [isn't interested in](https://github.com/fortinet-solutions-cse/fortiosapi/issues/76) SSH method for FortiGate made me fork the repository and fix it using [Fabric module](https://www.fabfile.org/). 


### How to install

Install from repository using your favorite Python package tool:
```
pip3 install git+<repository url>
```