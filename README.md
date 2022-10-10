# ESP32_OTAWeb_RTOS
Simplified example of ESP32 OTAWebUpdater

This is a simplified version of official example sketch comes from esp32 board manager. 
The original sketch has been modified as follows:

- made a header file (OTA.h) and included it from main program
- used FreeRTOS to execute server.handleclient()
