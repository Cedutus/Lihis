# Lihis
Lihis is a keyboard made by Eetu for Eetu. It's basically a worse Helix using a Blackpill.

![Lihis](/Assets/lortsyboard.jpg)
# Parts
 - 48x Hotswap sockets (MX or Choc or both)
 - 48x Diodes (Through hole or SMD)
 - 1x 10k resistor (Trough hole)
 - 2x Blackpill controller  (F401 or F411)
 - 2x Headphone jack
 - 12x 5mm or shorter M2 screws
 -  4x 12mm M2 spacer
 - 8x 10mm M2 spacer
 - 2x Rotary encoder with caps (optional)

# Build guide
 - Solder diodes on the PCB
 - Solder hotswap sockets on the PCB
 - Solder 10k resistor into one of the PCB's
 - Solder the headphone jack on the topside depending on your half
 - Solder Blackpills with the buttons facing up. B12 to Square pad
 - Optional: Solder rotary encoders

Firmware is not included in QMK repo, you will have to compile it yourself. Most of the code is copied and stripped down from Vattern's Grandiceps keyboard.
Blackpill bootloader: hold down the boot button on the blackpill, then press NRST. it might take some tries.
