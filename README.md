Smart Bulb Gui Controller
=========================

Contains a simple gui to control the power and brightness of Smart Bulbs. Currently only supports
Philips Hue (because this is what I own) - but the intention is to expand this to support any type
of smart bulb available with an API.

The next smart bulb to probably be supported is LifX

Dependencies
------------
Requires a Python 3 installation and PyGtk Installed on your machine.

Installation
------------
Run `./setup.sh` to setup a local virtual environement with the necessary dependencies

Running
-------

Specify the ip address of your Philips Hue bridge as an environment variable when running

```
SMART_BRIDGE_IP='192.168.0.22' python smart_bulb_gui.py
```
