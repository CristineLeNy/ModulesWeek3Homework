# ModulesWeek3Homework
*Click RAW to see proper format*


Voltage Regulators (Line and Adjustable)

Line Voltage Regulator:
datasheet for Regulator: 
  https://www.ti.com/general/docs/suppproductinfo.tsp?distId=10&gotoUrl=https%3A%2F%2Fwww.ti.com%2Flit%2Fgpn%2Flm3940
purpose: 
  This allows you to get an array of common voltages that you need to power your microprocessor and components without having to adjust the voltage regulator. 
design:
  This degin takes a nine volt battery and that goes into a voltage divider to give you 5 volt. it is done with a 1.2k resistor and a 1.5k resistor. Then it goes into a voltage regulator through a .47u farad capacitor that outputs a steady 3.3 volts. On the output of the 3.3volt regulator is a 33uF capacitor. The final voltage is taken across the 33uF capacitor. 

Adjustable Voltage Regulator:
datasheet for regulator:
  https://www.ti.com/lit/ds/symlink/lm117.pdf?HQS=dis-dk-null-digikeymode-dsf-pf-null-wwe&ts=1644591258174&ref_url=https%253A%252F%252Fwww.ti.com%252Fgeneral%252Fdocs%252Fsuppproductinfo.tsp%253FdistId%253D10%2526gotoUrl%253Dhttps%253A%252F%252Fwww.ti.com%252Flit%252Fgpn%252Flm117
purpose:
  With this design, you can get more precise value for the voltages. This allows you to more easily control the response of your system. 
design:
  For the design, there is a 9V battery that goes into a .1uF capacitor and into the regulator. From there there is a 10k adjustable resistor. The output goes then into a 330 ohm resistor and a 1uF capacitor. The final voltage is the voltage across the 1uF capacitor. 


Import: 
  To import the design into your schematic just download the .dch file. Then copy the design into the new schematic by highlighting over it. Once thatis done, you can make it into a hierachical block to add into your design. This saves space in th long run for schematics. 
