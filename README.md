# Electronic-Projects
Schematics and PCB board designs

The esp32SimpleRelay is a project that works from a 12v source probably a 
battery/solar setup. This is wifi so must be close to a wifi router or similar. 
Basicly a simple on/off relay, maybe for 12v led lights .
--currently esp32
--could use
  --zigbee (too expensive, long range, mesh network)
  --NRF24L01 (cheap, short range, star network)
  --433MHz modules (super cheap, long range, not a transceiver)
  --lora module ( expensive, long range, mesh network)
 
The tabelmini is a motor, valve etc. controller. Not designed yet to be for
industrial work. How it works: uses buttons to selected preprogrammed motor etc.
and user can select tests to be performed. or control the motor etc. directly. 
Possible connects to a PLC that controls the motor etc. and sends it commands 
wirelessly. or Directly connect using a port.
(working progress)
