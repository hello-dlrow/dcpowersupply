# DC Power Supply
This is a DC Power Supply with 3 Voltage options
- 5V DC Voltage
- -15.6V DC Voltage
- 1.3V~17.5V DC Voltage

<img src="https://github.com/hello-dlrow/images/blob/main/Pic/schematic.png?raw=true" width="600">



Using a transformer to step down 110V power to 33V AC, then rectify the AC voltage with a bridge rectifier.Then use an decoupling capacitors to input the filtered voltage into the regulator. 10ohms for voltage divider, because rated volatage of LM7805 is much lower.

Regulator Maxium Input voltage range:
- LM7805(5V output):5V
- LM7915(-15V output): -35V
- LM317(adjustable output): 40V

Voltage ripple
- 5V DC Voltage:
- -12V DC Voltage:
- 1.3V~17.5V DC Voltage:
