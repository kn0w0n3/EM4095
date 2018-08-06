
ESP32 porting library from RFIDino and Crypter ESP8266 library

You can use it with esp32 library for arduino, also use for other boards.

Unique change paramter is timeout

#define DELAYVAL    320   //384 //standard delay for manchster decode
#define TIMEOUT     7000  //standard timeout for manchester decode

1000 for arduino mega devices (16mhz)
about 7000 for esp32 and similar (80mhz)

All code work directly without special library request.

Enjoy it
Alex
