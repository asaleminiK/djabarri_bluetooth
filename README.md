ESP-IDF Gatt Server & Client
========================

This is a Bluedroid server demonstration. This project has no special purpose yet. There are two services, service A has any number of user-definable characteristics, and service B has one. This code is designed so a Bluetooth client can connect, write, and read from characterisitics, as well as listen to notifications.

BUGS
========================

No reported bugs.

TODO
========================

-Enable client to read from multiple characteristics
-Enable server to support 2 instances so iOS app can connect
-Enable FreeRTOS for SPI
