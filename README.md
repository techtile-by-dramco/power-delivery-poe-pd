# Power delivery board 

This powered device (PD) board is made for the Techtile infrastructure and separates the voltage from the data coming from the ethernet CAT6 24AWG cable. It further converts the voltage to a lower usable 5V voltage with a galvanically isolated dc/dc converter (maximum output power 20W). This board is compatible with the IEEE802.3af/at/bt standard. 

To comply with the IEEE 802.3 standard a delay network was added. This prevents excessive startup power that occurs due to the high input capacitors of the DC/DC converters. During INRUSH state, the power may not exceed Power Class 3 (approximately 13W). Otherwise, the PSE may turn off the PD. (See standard and datasheet NCP1096)

Several USBs and connectors are available to power the peripherals on each tile.