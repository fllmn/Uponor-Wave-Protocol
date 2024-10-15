# Uponor-Wave-Protocol
Reverse engieering Uponor wave wireless protocol

# Background
I recently bought Uponor Smatrix Wave T-165 and wanted to use if for a normal Zigbee radiator valve. I couldn't find anything online so I decided to do some investigation

# Hardware
The T-165 uses a R5F1026AASP#V0 MCU and a TI CC110L wireless transceivers. The CC110L is controlled over SPI. During startup the CC110L is configured for 868 Mhz and GFSK modulation.

# Operation
The thermostat communicate anything until it has paird to a control central. Pairing can be initiated by pressing and holding down the button on the back side

# Captured data

