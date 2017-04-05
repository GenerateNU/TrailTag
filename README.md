# TrailTag
TrailTag is a device that sends GPS data over the 915MHz radio band to other TrailTags in order to communicate position and distress signals without being connected to a cell phone.
<br>This repository holds the code for the transmission and reception of the RF packets that include the GPS data.
## Hardware Used
TrailTag is using the TI SimpleLink CC1350 MCU. This is because of its RF transmission capabilities, as well as it's low power usage, small size, and bluetooth transmitter/receiver (which will be used in the future).
<br>The GPS module used is the GNS 302uLP made by Global Navigation Systems. It is based on the MT3339 chip produced by MediaTek Inc.
