# minimal-fpc-i2c-pcb
Minimal adapter board for converting keyboard i2c oled pins to ffc/fpc ribbon cable for keyboards such as crkbd or kyria, intended to make using cirque glidepoint trackpads easier with keyboards that already have an OLED header.
<img width="841" alt="Screenshot_2022-07-07_at_13 14 48" src="https://user-images.githubusercontent.com/19674258/177773317-9b9e2e26-6b3b-4478-bfce-c52ee5c3ee93.png">


Connector used is this one from LCSC: https://lcsc.com/product-detail/FFC-FPC-Connectors_SHENZHEN-ATOM-TECH-FPC05012-09200_C479750.html (I am looking for a digikey equivalent)

To use the TM035035 and TM040040 with 5v controllers, on the back trackpad, remove R1 for I2C, and remove R7 and R8 for 5V (leave these if using with 3v3 controllers i.e. rp2040.
