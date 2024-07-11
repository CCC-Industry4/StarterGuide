# Configure Smart Home
---
1. Connect the demonstration PC to the Pi. Wi-Fi can be used on a PC or smartphone. The disadvantages of using Wi-Fi are that you will lose access to the internet. Connect to the following:
SSID (service set identifier): IT4Project
Password: IOT12345
2. Plug in and powerup Smart Home.
3. Connect to the IP address displayed on the Smart Home's LCD using a web browser.

4. Configure namespace of Smart Home using a web browser.
	
  -  Ask your instructor for the neighborhood and home number:
      -  Neighborhood number- should be the same for the whole class.
      -  Home number- must be unique for each home in the neighborhood.
  -  In industrial systems data is organized into a unified naming format following the ISA 95 standard:  
> Enterprise→Site→Area→Line→Cell  
  -  Research Unified Name Space (UNS) and the ISA 95 standard.  ([Here](https://www.hivemq.com/resources/smart-manufacturing-using-isa95-mqtt-sparkplug-and-uns/) is more info at HiveMQ website.
  -  The namespace structure for the Smart Homes on this system is
> Smart Homes Inc/Neighborhood #/Home#

*Note: Technically this doesn’t follow the ISA standard in that the namespace is truncated.*

  -  **Determine the correct namespace** for your home and **add **it to the system.  Pay careful attention to spaces.  
  -  **Click Change.**
  -  **Click Finalize and Reset.**
5. **Verify** that your Smart Home is working. 
  -  **Press CLOUD** then **LOCAL** buttons on the SCADA to cause the dropdown to include the new number.
  -  **Select** the new home number in the dropdown.
  -  If you see the count increasing simultaneously on the house and on the SCADA system on the web browser, you have successfully set-up the Arduino Smart Home.
6. You can not have two smart homes with the same namespace.  If your home doesn’t connect, look at the namespace of working SmartHome. 
7. Demonstrate to your instructor.
