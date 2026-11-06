[Back to Main Menu](https://github.com/CCC-Industry4/IIOT-4.0-Project/tree/main)
# Ignition Configuration

# Downloading Ignition Gateway on a PC
Downloading ignition to your respective OS can be frustrating for some because when you select a version you want to download it can ask you for a lot of information.
1. The first step is to go to this link and install a version of ignition with the characteristics 8.3.xx, this [link](https://inductiveautomation.com/downloads/archive/8.3.4) takes you to version 8.3.4
2. Depending on how your PC is set up (e.g, if your computer has installed ignition before or not) ignition might ask you for some information when trying to install it.
   - For the first and last name you can put yours
   - For company name you can put your school's name
   - For email you can put your school email
   - For the phone number if you don't feel comfortable putting your own then you can ask your instructor what to put here
   - Role should be set to Jobseeker/student
   - "Are you an integrator" should be set to no
  
## Restoring gateway

To install the MQTT modules for Ignition, you must do the following (see this video for more information): [Video Link](https://youtu.be/AB4knX_4n5c)
1. Use this [link](https://inductiveautomation.com/downloads/third-party-modules/8.3.4) and download the ones that start with MQTT (Distributor, Engine, Transmission, Recorder)
2.  Type http://localhost:8088 into a web browser
3.  Log in with the default ignition credentials unless they have been changed (username = admin, password = password).
4. On the left hand side of your screen click the tab that says "Platform", click system, and finally click modules
5. In the upper right-hand corner click the blue button that says "Install or upgrade module"
6. Click choose file and install all the .modl files that start with MQTT that you just downloaded.

# Configuring MQTT Engine Module on Ignition
1. Click "Configuration" on the lefthand side
2. Click MQTT Engine and then configuration
3. Click the three dots on the "MQTT_Broker" and type "tcp://localhost:1883" into the URL box.

# Ignition Licenses for Education
Ignition allows individuals to use full ignition on a two-hour resettable trial basis indefinitely for non-commercial use.  Alternatively Ignition Maker Edition, a streamed down version, may be used for personal use without the need for resetting, but must be connected to the internet.  Inductive Automation partners with qualifying educational institutions to provide free Ignition licenses to students anywhere in the world! Apply here: [https://inductiveautomation.com/educational-engagement](https://inductiveautomation.com/educational-engagement)

---
