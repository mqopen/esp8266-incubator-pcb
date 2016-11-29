# ESP8266 Incubator changelog

## v0.1.0

 - First board design.
 - Intended to be manufactured by [dirtypcbs.com](http://dirtypcbs.com/).
 - Powered by mini DC-DC power supply module ([LM2596](http://www.ti.com/lit/ds/symlink/lm2596.pdf) chip).
 - 5.5 mm center positive jack.
 - On-board programming connector.
 - Programming push button.
 - Jumper for enabling power supply module.
 - SMD notification LED.
 - Two relays in series for driving heater circuit.
 - Two screw terminals for connecting heaters.
 - 12V screw terminal for controlling fan.
 - Piezo buzzer for alarm signaling.

## v0.1.1

 - Schematics splited into multiple sheets.
 - Added PWR_LED.
 - Alarm buzzer is switched using N-MOSFET.
 - Added ALARM_LED.
 - Relays are controlled using MOSFET.
 - Fixed logic of RELAY_NC.
 - Added RELAY_LED.
 - Fan is controlled using N-CHANNEL and P-CHANNEL MOSFETS.
 - Added FAN_LED.
 - Added RST button.
