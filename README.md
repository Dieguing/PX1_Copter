# PX1_Copter

This is a copy of Ardupilot project Copter/Plane 4.5.

# Requirements
- pip install empy==3.3.4 --break-system-packages
- python -m venv .venv && source .venv/bin/activate
- pip install -r requirements.txt

# Init / config
./waf configure --board pixhawk1

## Compile
./waf copter

## Upload
./waf --targets bin/arducopter --upload

## Example
./waf --targets examples/UART_test --upload