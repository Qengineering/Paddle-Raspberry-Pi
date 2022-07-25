# Paddle 2.3.1 for the Raspberry Pi 4 Bullseye 64-bit OS
Paddle installation files for the Raspberry Pi 4 with 64-bit operating system
For the installation guide see [Install Paddle 2.0.0](https://qengineering.eu/install-paddlepaddle-on-raspberry-pi-4.html) <br/>

--------

# Paddle 2.0.0 for the Raspberry Pi 4 Buster 64-bit OS
Paddle installation files for the Raspberry Pi 4 with 64-bit operating system
For the installation guide see [Install Paddle 2.0.0](https://qengineering.eu/install-paddlepaddle-on-raspberry-pi-4.html) <br/>

--------

## Dependency
```
# install dependencies
$ sudo apt-get install cmake wget
$ sudo apt-get install libatlas-base-dev libopenblas-dev libblas-dev
$ sudo apt-get install liblapack-dev patchelf gfortran
$ sudo -H pip3 install Cython
$ sudo -H pip3 install -U setuptools
$ pip3 install six requests wheel pyyaml
# upgrade version 3.0.0 -> 3.13.0
$ pip3 install -U protobuf
# download the wheel
$ wget https://github.com/Qengineering/Paddle-Raspberry-Pi/raw/main/paddlepaddle-2.0.0-cp37-cp37m-linux_aarch64.whl
# install Paddle
$ sudo -H pip3 install paddlepaddle-2.0.0-cp37-cp37m-linux_aarch64.whl
# clean up
$ rm paddlepaddle-2.0.0-cp37-cp37m-linux_aarch64.whl
```
## Wheels
Please find your **linux-aarch64** installation wheel here. The **cpXX** number refers to your Python3 version.<br/>
Ubuntu 20.04 (Python 3.8) -> Put a request!<br/>
Ubuntu 18.04 (Python 3.6) -> Put a request!<br/>

----

Please notice, this is the full Paddle package, not the Paddle Lite version for small devices and mobile phones.<br/>
For this guide of Paddle Lite see [Install Paddle Lite](https://qengineering.eu/install-paddle-lite-on-raspberry-pi-4.html) <br/>

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 
