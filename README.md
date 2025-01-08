# PX1_Copter

This is a copy of Ardupilot project Copter/Plane 4.5

# Init / config
./waf configure --board pixhawk1

## Compile
./waf copter

## Upload
./waf --targets bin/arducopter --upload

## Example
./waf --targets examples/UART_test --upload