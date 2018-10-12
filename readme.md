# platformio debu project

Default project for debugging purposes.
Blinks on any operation and prints to serial result

## Installation
`brew install platformio` -- install platformio

## Dependencies
none

## Build and tasks
`pio run` -- build everything  
`pio run --target upload` -- build and upload to arduino
`pio run --target upload, monitor` -- build, upload and monitor serial output

## Hardware:
Arduino UNO

## Additional info
Everything works by COM protocol, tested on `atmega328p`
Project is based on [platfromio](http://docs.platformio.org/en/latest/)
