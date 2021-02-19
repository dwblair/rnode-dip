# rnode-dip

## Credits

DIP version of [rnode](https://github.com/markqvist/RNode_Firmware/) by [markqvist](https://github.com/markqvist).

See original design [here](https://github.com/markqvist/RNode_Firmware/tree/master/Schematics).

## References

[atmega1284p-pu (dip) on digikey](https://www.digikey.com/en/products/detail/microchip-technology/ATMEGA1284P-PU/1914521)

Likely SX1276 LoRa breakout board used in original rnode [here](https://www.ebay.com/itm/SX1276-Wireless-LoRa-Module-Semtech-IoT-868MHz-Transceiver-inAir9-/281866635993)

Pic of module: <img src="/ref/semtech_full.jpg">

Pic of pinout (looking down from top): <img src="/ref/semtech.gif">

Pins (from that diagram, matching original schematic):

RHS:
1. DIO5
2. 
3. MOSI
4. MISO
5. SCK
6. 3.3V

LHS:
1. DIO2
2. DIO1
3. DIO0
4. RST
5. DIO3
6. CS
7. GND

Pic of original rnode: <img src="/ref/rnode_original.jpg">

## Arduino Board definition for RNode

Discussed [here](https://unsigned.io/board-support-in-arduino-ide/)


## Bootloader

Not yet sure how to do this. Some useful-seeming hints:

- [http://www.technoblogy.com/show?19OV](http://www.technoblogy.com/show?19OV)
- [https://github.com/maniacbug/mighty-1284p](https://github.com/maniacbug/mighty-1284p)


