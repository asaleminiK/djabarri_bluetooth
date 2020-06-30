ESP-IDF Gatt Server & Client
========================

This is a Bluedroid server demonstration. This project has no special purpose yet. There are two services, service A has two characteristics, and service B has one. This code is designed so a Bluetooth client can connect, write, and read from characterisitics, as well as listen to notifications.

BUGS
========================

Service A does not support notifications yet. This is an issue with handles.

TODO
========================

-Create the Client codebase 
-Fix Notification handling
-Enable FreeRTOS for SPI
