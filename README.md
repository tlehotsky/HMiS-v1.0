HMiS-v1.0
=========

Home Managment information systems ver 1.0

This project is to construct a hardware platform to measure  and monitor an environment.  
I envision the environment to eventually be a data center or some other type of technology space.  
For now the test environment will be my home.  
For an enterprise facility a system like this would be called a Building Management System (BMS), for this project I coined the acronym
HMS for Home Management Information System.
Some of the functional requirements I have envisioned for the HMiS include:

Temperature Monitoring for the Following
Each floor (basement, first, second, attic)
Each bedroom
Outdoor – direct exposure to sun
Outdoor – under shade
Refrigerator (both compartments)
Outdoor grill (to detect if in use)
 
Monitor Conditions of the Following
Garage Door Position
Basement lights
Rain Level
Presence of standing water in basement
Overall Power usage
Power usage per bedroom
Frig door position
 
Control the Following
Outdoor Sprinkler and drip irrigation system
HVAC return air damper to introduce outside air to  cooling system when outside conditions are ideal
 
Output Systems
Wall mounted 20″ display with 4 static screens of information
External web page
SiriProxy
 
Away Mode (check that certain conditions are in order before leaving the property)
Garage door closed
basement and attack lights out
Stove is off
Grill is off
 
Front Door monitoring
Send alert when the presence of a person is detected (using sonar) at front door
Show camera image of front door when doorbell is depressed
 
There is no shortage of information on the internet in regards to the Raspbery PI, 
and the intent of this blog is not to educate one on the topic.  Simple stated it is a full fledge computer on a board, 
complete with (2) USB, HDMI 1/8” audio and an ethernet port.  
Remarkably it is about the size of an Altoids case and costs $35.
There were two reasons for creating this blog.  
First, as I progressed through the various steps of building this I became nervous that if I experienced a hardware failure and needed to rebuild I would forget some of the critical steps.  Secondly, in the research I performed, I don’t recall seeing a a complete start to end tutorial for building a Raspberry PI project – I’m sure its out there – I just haven’t seen it..
