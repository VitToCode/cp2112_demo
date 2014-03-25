cp2112_demo
===========
* Copy SLABHIDDevice.dll and SLABHIDtoSMBus.dll (from lib/x64/ or lib/x86/) to Solution (i.e. top-level) "Debug" folder before running application
* Ensure SDA and SCL lines are pulled-up to the voltage matching that of the battery interface:  
 * Set J7=EXT_PU and connect TB1(EXT_PU) to the battery interface voltage  
 * If 5V is not externally available for a 5V SMBus interface, connect TB1(EXT_PU) to J5(1) VBUS.

**Program Output:**  

*C:\Users\Nick\Desktop\cp2112_demo\Debug>cp2112_demo.exe*  
*Device successfully opened.*  
*Device successfully configured.*  
*Voltage = 11863 mV*  
*Current = -18 mA*  
*RSOC = 77 %*  
*Remaining Capacity = 1702 mAh*  
*Average Time to Empty = 5673 min(s)*  
*Done! Exiting...*  

*C:\Users\Nick\Desktop\cp2112_demo\Debug>*
