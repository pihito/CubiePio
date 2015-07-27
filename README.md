CubiePio
========

This program is based on pio sunxi tools but it works on Cubitruck lunbutu.
with this tools you don't need to change fex file.

To setup a pin :
pio -m PINBR/mode/pullup/drive/value

PINBR : for pin number on extension port see : http://linux-sunxi.org/Cubietruck#Expansion_Ports

for the mode is are : 0 for input, 1 for output and for other see mux on : http://docs.cubieboard.org/a20-cubietruck_gpio_pin

activate the pullup : 1 or 0 to disable

drive : defines the output drive in mA, values are 0-3 corresponding to 10mA, 20mA, 30mA and 40mA.

value : 0 or 1

sample : sudo pio PC21/1/0/0/1 put the pin PC21 (near the ethernet port) at 3,3V
