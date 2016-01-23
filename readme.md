## Yotta target
Yotta target description using GCC to compile for Nordic nRF51 16KB V3 IC
Ideal for bareminimun boards / modules and custom circuits.

It uses the internal RC clock at boot, 16Kbyte of RAM, the S110 softdevice

The project is forked from the nrf51dk-gcc target by Mbed.
The pin names are the same.

###installation

To be sure that the target is correctly installed, modify your yotta.json file as follows:
'''
{
  "build": {
    "target": "nrf51bareic-gcc,fermiumlabs/target-nrf51bareic-gcc"
  }
}
'''

To install the target run:
'''
yotta target nrf51bareic-gcc
'''

To update all your project dependencies including our target from the master branch run:
'''
yotta up
'''


###Site:
Please visit https://fermiumlabs.com to be kept update on our projects
