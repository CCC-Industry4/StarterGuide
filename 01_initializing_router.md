# Initialize Router
---
Please this this [Helpful Link](https://www.tomshardware.com/how-to/static-ip-raspberry-pi) on how to Set a Static IP Address on Raspberry Pi

In order to run the project, you must have a router to avoid firewalls. The way we chose to do this was to buy a cheap router and configure it to this setting:  
> **Name:** IT4 Project  
> **Password:** IOT12345  
> **LAN IP Address:** 192.168.10.1  


The Raspberry Pi must also be configured with a static IP address. You can either do that through the router or dhcpcd.conf file. A helpful article for the second method is included in the link above.  
The router being used for this project is [GL.iNet Shadow]([GL-AR300M16-Ex](https://store-us.gl-inet.com/products/gl-ar300m16-mini-smart-router)t), but most any router could be used.
The steps to setup the router are as follows:  
1. Power on: Plug the micro USB power cable into the power port of the router using a standard 5V/2A power adapter.
2. Connect via Wi-Fi:
The SSID is printed on the bottom label of the router with following format:
GL-AR300M-XXX-NOR
Input default password: goodlife
3. Access the web Admin Panel:
Open a web Browser (Chrome, Firefox are recommended) and visit http://192.168.8.1.
Language Settings
Choose the display language of the Admin Panel and Click Next.
- Admin Password Setting:
- There is no default password for the Admin Panel. Set password to IOT12345 and click Submit.
- Admin Panel
- After the initial setup, the web Admin Panel of the Router will be displayed.

Setup SSID and Password:
Select Wireless from the Menu on Left side and click Modify



Change Wifi-Name (SSID) to IT4 Project
Set Wi-Fi Key to: IOT12345
Click Apply.
The Wifi-Name and password should be set. Reconnect to the Wi-Fi using the new login.
Setup IP Address:
Under More Settings, select LAN IP, from the left menu bar.
Change the LAN IP to 192.168.10.1, Click Apply.

The Router is now correctly set up. The admin Web page will now be accessed by visiting http://192.168.10.1.

---
Next: 
