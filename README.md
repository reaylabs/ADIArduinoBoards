# ADIArduinoBoards
Repository for custom Arduino boards.

## Supported Boards
### ADIInstrument
### RL2000
### CompProbe
  <li>Based on ItsyBitsy M0 Express</li>
  <li>Upgraded to a USBC connector for increased current capability.
  <li>VBus and VBat diodes, D5 level shifter, SPI flash and dotstar removed.</li>
  <li>2k I2C EEprom added at address 0x50 for storing calibration data.</li>
  </ul>
  <br>

## Arduino IDE Setup Instructions

<li>Copy and paste the following URL into the File > Preferences > "Additional Boards Manager" textbox.

```
https://raw.githubusercontent.com/reaylabs/ADIArduinoBoards/master/CustomBoards/package_adi_index.json
```
</li>
<li>
Go to Boards > "Add board definition" > Search for "Analog Devices" > Install ADIArduinoBoards library
</li>
<li>
Go to Boards > "Add board definition" > Search for "SAMD" > Install Arduino SAMD Library
</li>