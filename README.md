# aquarium_reconnect
The project uses a water pump, a water sensor, a relay, and an Arduino Uno to make the aquarium filter work automatically after a power outage.

Water pump: STJF 5V submersible pump
Water sensor: T1592 (default sensor in most kits, red circuit board)
Relay module: 5V single relay module
Board: Arduino Uno

--- WIRING ---

Water sensor:
VCC: D7
GND: GND Arduino output
Signal: A0

Relay:
VCC: 5V Arduino output pin
GND: GND Arduino output
Signal: D3
Common (COM): 5V Arduino output pin
Normaly Open (NO): water pump red wire

Water Pump:
+: NO relay port
-: GND Arduino output
