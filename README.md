[![4relay-rpi](readmeres/sequent.jpg)](https://www.sequentmicrosystems.com)

# 4relay-rpi

[![4relay-rpi](readmeres/4-RELAYS.jpg)](https://sequentmicrosystems.com/product/4-relays-heavy-duty-stackable-card-for-rpi/)

This is the command to control [4-RELAYS Heavy Duty Stackable Card for Raspberry Pi](https://sequentmicrosystems.com)

Don't forget to enable I2C communication:
```bash
~$ sudo raspi-config
```

## Usage

```bash
~$ git clone https://github.com/SequentMicrosystems/4relay-rpi.git
~$ cd 4relay-rpi/
~/4relay-rpi$ sudo make install
```

Now you can access all the functions of the relays board through the command "4relay". Use -h option for help:
```bash
~$ 4relay -h
```

If you clone the repository any update can be made with the following commands:

```bash
~$ cd 4relay-rpi/  
~/4relay-rpi$ git pull
~/4relay-rpi$ sudo make install
```  

Python driver can be found [here](https://github.com/SequentMicrosystems/4relay-rpi/tree/master/python).

Node-Red example basd on "exec" node [here](https://github.com/SequentMicrosystems/4relay-rpi/tree/master/python).

Node-Red "4relay" node under construction.

[CODESYS Driver](https://github.com/SequentMicrosystems/4relay-rpi/tree/master/CODESYS)
