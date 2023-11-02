# Garagedoor opener for ESPHome
Garagedoor opener based on the work of Alex Reid (https://reid-projects.com/control-garage-door-home-assistant-esphome-budget/) . 
Since I have two garagedoors I needed to duplicate the code so that it works for booth doors.

You can of course use this for only one door.

Hardware:
- NodeMCU ESP8266
- Wiring
- 4 Reed sensors in total (one in the open and closed position of each garagedoor).
- Two-channel relay

Configuration:
- Change "delay" to the value your garagedoor uses to close or open. Any time over this limit results in error in Home Assistant.

Connect the relay and Reed sensors according to the code (named Dx).
- Garagedoor 1
  - Relay D1
  - Reed open position D6
  - Reed closed position D5

- Garagedoor 2
  - Relay D2
  - Reed open position D4
  - Reed closed position D3

Connect Relay + to VIN and Relay - to GND
Connect the Reed sensors to GND
