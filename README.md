# Win-Test-RS485-GHz-Switch
This is a simple Lua script for Win-Test for switching the GHz bands (transverters, coax relays etc.) using a Modbus_Relay X8_V2 card.

(C) 2026 Jens Wagner, DH1AKY

Credits: Thanks to Laurent (Larry) Haas, F6FVY and Bob Wilson, N6TV for the tips creating that code.

The code is released under GPLv3

# Relay coding
The relays in this example are used as followes

["144"]  = "FF050000FF0099E4", -- Relay 1 (2m) 
["432"]  = "FF050001FF00C824", -- Relay 2 (70cm) 
["1296"] = "FF050002FF003824", -- Relay 3 (23cm) 
["2320"] = "FF050003FF0069E4", -- Relay 4 (13cm) 
["3400"] = "FF050004FF00D825", -- Relay 5 (9cm)  
["5700"] = "FF050005FF0089E5", -- Relay 6 (6cm)  
["10G"]  = "FF050006FF0079E5", -- Relay 7 (3cm)  
["24G"]  = "FF050007FF002825"  -- Relay 8 (1.2cm)

#Improvements: 
One relay maybe used as default switched to a dummyload for resilance.
