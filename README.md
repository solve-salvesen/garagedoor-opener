Garagedoor opener based on the work of Alex Reid (https://reid-projects.com/control-garage-door-home-assistant-esphome-budget/) . 
Since I have two garagedoors I needed to duplicate the code so that it works for booth.

Hardware:
- NodeMCU ESP8266
- Wiring
- Magnet sensors in the open and closed position of the garagedoors
- Two-channel relay

Configuration:
Change "delay" to the value your garagedoor uses to close or open. Any time over this limit results in error in Home Assistant.

Connect the relay and magnet sensors according to the code (named Dx).
Garagedoor 1
- Relay D1
- Magnet open position D6
- Magnet closed position D5

Garagedoor 2
- Relay D2
- Magnet open position D4
- Magnet closed position D3
