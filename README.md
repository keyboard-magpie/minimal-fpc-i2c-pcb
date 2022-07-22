# minimal-fpc-i2c-pcb
Minimal adapter board for converting keyboard i2c oled pins to ffc/fpc ribbon cable for keyboards such as crkbd, kimiko or kyria, intended to make using cirque glidepoint trackpads easier with keyboards that already have an OLED header.
<img width="841" alt="Screenshot_2022-07-07_at_13 14 48" src="https://user-images.githubusercontent.com/19674258/177773317-9b9e2e26-6b3b-4478-bfce-c52ee5c3ee93.png">



# how to use
To use the TM035035 and TM040040 with 5v controllers, on the back trackpad, remove R1 for I2C, and remove R7 and R8 for 5V (leave these if using with 3v3 controllers i.e. rp2040.

# holders
In the holders folder you will find holders for the 40mm cirque for popular keyboards!

# production
Please note there is a small error in the cpl file for the ffc connector that comes from the footprint for it. JLC should correct its placement for you.

Connector used is this one from LCSC: https://lcsc.com/product-detail/FFC-FPC-Connectors_SHENZHEN-ATOM-TECH-FPC05012-09200_C479750.html

# alternative FPC connectors: 
https://www.digikey.co.uk/en/products/detail/hirose-electric-co-ltd/FH12-12S-0.5SH-55/1110374 
https://www.digikey.co.uk/en/products/detail/gct/FFC2B35-12-G/15970866
Both of the above were suggested by u/idyllic on discord and look to have a footprint that is very close the the LCSC part above and should be compatible.

# ffc/fpc cables
Any generic flat flex cable can be used, they are 12 position, 0.5mm pitch, same-sided contacts. The molex extra flex and primo flex series from mouser seem to work well.
