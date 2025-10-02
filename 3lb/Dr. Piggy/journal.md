---
Title: Dr. Piggy - 3lb Combat Robot
Author: Aaron Zhan
Description: A 3lb :Beetleweight" Combat Robot
Commenced On: 9/1/2024
---

---
**Date: 9-28-25, Time Logged: 3 hrs**

<img width="350" height="600" alt="image" src="https://github.com/user-attachments/assets/b9e0b37f-8d42-4a3c-afed-99d40df16586" /><img width="450" height="600" alt="image" src="https://github.com/user-attachments/assets/ccf4c8aa-a42f-49e7-8dcb-1ce7f2443099" />


As you can see, I am closing in on 200 versions! That means, I edited, improved, and saved that exact file 200 times! This project has been ongoing for almost a year now! However, the log begins here:
This is a rundown of what I had accomplished over the past year:
- 3lb combat robot
- primarily 3D printed
- using off-the-shelf drone components (motors, escs, etc.) 
- Drisk weapon, TPU hub w/ metal standoffs (m5)
- Tangental drive w/ belt tensioners
- 3D printed TPU belts, belt tensioners (m5 leadscrew) necessary
- majority of fasteners: m3 nuts and screws
- modular wedge/fork mounting setup
- swag can be engraved onto body

Ideas I'll probably do:
- A fan on the motor that has a duct directed at the electronics

Here is what I accomplished today:

I started out with creating the parameters for the m3 hardware (nuts and screws). That way, I can adjust clearance for every instance of m3 hardware all at once, instead of manually changing, one-by-one. 
Then, I did a bit of "housekeeping", brushing up on some geometry: 
- I added spacers between my drisk weapon disks to increase space for the weapon belt tensioner
- Increased strength (width) of weapon belt tensioner
- I fixed the geometry for the drive belts (from 8mm wide to 6mm wide, reduced interference with the wheels)
  - I think I might need to rework the drivetrain - the bearing setup seems a bit unreliable. However, this may be difficult since I am using a tangental drive setup.
  - Fixed drivetrain compliant TPU wheel geometry
- Split main body into two: I will need to create a connection system (future to-do)

**Date: 10-02-25, Time Logged: 2 hrs**
<img width="981" height="568" alt="image" src="https://github.com/user-attachments/assets/16cb3596-d1bf-4822-b195-dd5f41988898" />
<img width="913" height="587" alt="image" src="https://github.com/user-attachments/assets/ab423454-e88d-4428-bbdb-e54a73da2593" />


On this session, I worked more on polishing the robot. I have made a pretty significant decision to split the robot's general chassis into two parts. This way, I can have shorter 3D print times, meaning s smaller chance of print failure. To execute this, I added mounting points and connections.
I also created a "fan-duct" channel. The goal is to mount a fan on the weapon motor, and while it spins the drisk weapon, the fan is also spun. The fan's air will be directed into the electronics, cooling it down.
