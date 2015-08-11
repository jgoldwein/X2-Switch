# X2-Switch

Modified SmartSense (PEQ) Open/Closed Sensor to behave like TWO x 3-WAY on/off toggle switches 
   Requires this device type linked to X2-Switch: Modded 2-Switch App 
   Copyright 2015 - Joel Goldwein
   Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except
   in compliance with the License. You may obtain a copy of the License at:
 
       http://www.apache.org/licenses/LICENSE-2.0
 
   Unless required by applicable law or agreed to in writing, software distributed under the License is distributed
   on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License
   for the specific language governing permissions and limitations under the License.
 
 	This Device Type uses a single modified (hacked) SmartSense door open/close sensor wired to both an SPDT (3-way) 
  switch and a standard SPST wall switch, each of whicn can toggle on and off a set of GE Link Lights or similar 
  lights or switches.   
 
  The intent is to have a simple and inexpensive battery operated replacement for a standard wall switch to 
  operate multiple, 3-way zigbee or zwave lights or switches as well as a one way light or switch using two
  separate standard switches in an existing gang-box.
  
  The SmartSense (PEQ) sensor has been on sale intermittently at Best Buy for under $20, and a 3-way SPDT plus a
  standard wall switch costs a few dollars at any hardware store, so you can put the whole thing together for 
  about $25.00.
 
  The SmartSense door open/close sensor can be easily modded and wired to the 3-way wall switch and the standard
  wall switch as follows:
  
    1. Replace (desolder) the reed relay with 3 wires connected to a 3-way wall switch.  
    2. Replace (desolder) the small push button switch with 2 wires connected to a standard on/off wall switch. 
    3. Provision the "Thing" (make sure you put the standard switch into OFF mode since ON mode at battery installation
       causes it to reset), and replace the device type with:
       "X2-Switch: Modded SmartSense Open/Closed Sensor/Switch: TWO Switch Version"
    4. In selected gang box, have a certified electrician wire the GE link lights that will be used to remain ON
       by removing the existing switches and tying together the now hanging On-Off wires.
       Cap any "red" wires or otherwise exposed wires.
    5. Install the new switches and Thing into the gang box or a new gang box (use standard electrical safety measures). 
    6. Use the "X2-Switch Control: 2-Switch Control for Modded SmartSense Open/Closed Sensor/Switch for Multiple Lights"
       App to control the lights 
