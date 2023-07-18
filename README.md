# Super-T
This repository contains the files for operating the Super-T Dot Product Engine (DPE) chip of the Emerging Accelerator Teams at Hewlett Packard Labs. This code was created by Can Li in 2019.

### Quick Start

(1) Get all the packages you'll need to run the code.
$ pip install -r requirements.txt

(2) Open Jupyter lab environment.

(3) Plug in USB cables to PIC microcontroller. Open 'Device Manager'. You will see two USB COM ports become active in the Device Manager list under 'Ports'. One of these COM ports will be the communication to the PIC that you will need to change in the python code. The other COM port is a 'listening' port to check that the PIC is active. If you want to use this monitoring, open Putty (or other SSH/serial utility), specify a serial connection on (e.g.) COM9 with speed 115200. 