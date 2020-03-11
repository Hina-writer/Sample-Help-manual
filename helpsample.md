# Standalone Fail-Secure Electric Lock

  ### Installation Pre-requisites: 
  
  - [x] Controller Pro 
  - [x] 24 V Uinversal AC power supply (provided with the Kisi Controller Pro)
  - [ ] 12 or 24V DC [electric strike or magnetic lock](https://www.getkisi.com/guides/electronic-locks)
  - [ ] Ethernet Cable
  - [ ] Low Voltage Wires. 

## How to wire a Controller PRO to A FAIL-SECURE door lock?

                                               
![Standalone fail secure electric lock](https://user-images.githubusercontent.com/59232344/74480839-92598000-4ea9-11ea-9b64-f4c11ddcb011.png)

[![Standalonefailsecurevideo](https://user-images.githubusercontent.com/59232344/73980299-dc7db700-4927-11ea-85ba-56cb330ad888.png)](https://youtu.be/AR7dXvml0TE)


1. Wire one of the four relays to the fail-secure lock on the door. This is a wet contact relay which will require        positive wires to run to the 12V or 24V (depending on your lock) and negative wires to connect to the **NO (Normally Open)**.

2. Configure the jumper wire to run from **GND (Ground)** to **COM (Common)**.

| :warning: | Make sure the door lock is not connected to **GND** and **NC (Normally Closed)**. Such a configuration will burn out the fail-secure lock over time. |
 |---------------|:------------------------

   * The Kisi Controller Pro only supplies a total of up to 4 Amps power for the door locks from the circuit board. If you wish to power up more doors, please keep in mind, **not** to exceed a total of 4 Amps for **each** Kisi Controller Pro. <br>For instance, if there are two electric strikes which draw 12V/2 Amps from the Kisi Pro, **do not** power anymore locks from the circuit board. It is still possible to wire two more door locks to the Kisi Controller Pro as **dry contacts**, provided they have their own separate power supplies.</br>
   
 | :warning: | The Kisi Controller Pro does **not** support AC wiring, please ensure the lock is also compatible for DC wiring.  |
 |---------------|:------------------------
 

3. Power the Controller Pro, using the power supply and input provided. 
4. A blue light will turn on, indicating that the controller is powered.
5. Plug in the Ethernet cable. 
6. A green light will flicker at the top right hand corner of the board. This indicates that the Kisi Controller Pro is online. 



    | :hammer_and_pick:    | Oops, there is no green light? Not to worry, please visit our [troubleshooting guide](https://help.kisi.io/hc/en-us/articles/115009339068-Network-Settings-for-Controller-Pro-), to see what you might have missed! | 
    |---------------|:------------------------|
    
    
  <br></br>  
    
    
   
# External Power Supply & Fail-Safe Electric Lock with REX & Motion Sensor.

## Essential Items included:

-  Control Pro
- 24V Universal AC power supply.

## Additional Items required:

- 12 or 24V DC fail-safe [electric strike or magnetic lock](https://www.getkisi.com/guides/electronic-locks)
- Ethernet Cable
- Low Voltage Wires
- [External Power Supply](https://www.altronix.com/products/AL600ULACM) for lock
- Push to exit button/motion sensor
- Keypad.

## How to wire the External Power Supply and Fail-Safe Electric Lock with Rex and Motion Sensor and a Push to Exit Button?

![REX and Motion Sensor](https://user-images.githubusercontent.com/59232344/74480741-676f2c00-4ea9-11ea-9348-803c34b06166.png)

 
 [![External Power Supply   Fail Safe Electric Lock With REX   Motion Senso](https://user-images.githubusercontent.com/59232344/74462778-ae98f500-4e88-11ea-80dc-34c67e26038d.png)](https://youtu.be/H0vQgyN_pN0)

1. Connect the **Negative (-)** wire from the Maglock 
![maglock](https://user-images.githubusercontent.com/59232344/74379035-e9465300-4dde-11ea-9b9a-68a5bf09b652.png)  with the **NC (Normally Closed)** connection on the Push to Exit Button
![PushtoExitbtn](https://user-images.githubusercontent.com/59232344/74375105-a2089400-4dd7-11ea-8b81-09e699ffc002.png).

2. Build a connection between the **COM (Common)** from your Push to Exit Button ![PushtoExitbtn](https://user-images.githubusercontent.com/59232344/74375105-a2089400-4dd7-11ea-8b81-09e699ffc002.png) with **COM (Common)** on the Motion Sensor ![Motion Sensor](https://user-images.githubusercontent.com/59232344/74411395-0278ef00-4e33-11ea-9697-c8219573b24d.png).

3. Link the **NC (Normally Closed)** connection of the Motion Sensor ![Motion Sensor](https://user-images.githubusercontent.com/59232344/74411395-0278ef00-4e33-11ea-9697-c8219573b24d.png) with the **COM (Common)** connection of the Power Supply's output.

4. Connect the **Positive (+)** wire from the Maglock![maglock](https://user-images.githubusercontent.com/59232344/74379035-e9465300-4dde-11ea-9b9a-68a5bf09b652.png) with the **NC (Normally Closed)** connection of the Power Supply's Output.

5. Finally, connect the low voltage wiring from **GND (Ground)** on the Kisi controller with the **GND (Ground)** on the Power Supply's Input and connect the **NO (Normally Open)** on the Kisi controller with the **IN (Input)** from the Power Supply's Input.

 <br></br>  

# Wiring Contact Sensors and Request to Exits (REX)

### How to Wire Contact Sensors and Request to Exits (REX)?

The System allows you to attach [Contact Sensors](https://www.smarthome.com/seco-larm-sm-200q-wh-surface-mount-magnetic-contact-switch-normally-closed.html?gclid=EAIaIQobChMI9I7rsfvJ3AIVBIrICh1DaQfGEAkYASABEgKaZ_D_BwE) or Request to Exits ([Push to Exit button](https://www.alarmcontrols.com/en/products/push-buttons/electronic-timer-push-buttons/ts-2t/) and [Motion Sensors](https://commerce.boschsecurity.com/us/en/Product-Segments/c/1)), directly with your Kisi Controller: 


![Wiring Contact Sensors and Request to Exits (REX)](https://user-images.githubusercontent.com/59232344/74479733-a13f3300-4ea7-11ea-9535-423d3aceebc4.png)


1. Connect wires from either the Contact Sensor or Request to Exit (or both), with the Input Channels of their respective relays.  

2. Once connected, configure them in Kisi's Dashboard software. 


| :pencil:  | For more information on how to configue Contact Sensors and REX with Kisi's Dashboard, please refer to the ["Create and Configure Doors"](https://help.kisi.io/hc/en-us/articles/115009339548-Create-and-configure-doors) guide. 
|----------------|:---------------|
