![Heading](https://github.com/xyberviri/Starbase/blob/main/YOLO/Heading/Heading.jpg)

# Ship Heading & Angle
This script uses two ISAN systems to figure out the ships heading and the angle the ship is pointed.


# Setup
1. Have two Working ISAN Mono or Quad systems, either isolate the systems or rename variables  
2. Place main ISAN system at the center of the ship
3. Place heading ISAN some where at the front of the ship, ideally maintain the height and centering.
4. Have one Memory chip with the fields XX, YY, ZZ, X2, Y2, Z2. 
5. Have a text-panel with it's field renamed to "Heading"

# Optional
1. If using the included ISAN_2.yolol script add a 2nd hybrid panel with the name of "i"
2. Add a 2nd ship navigation reciver and name the strength field to "e" and the target message field to "et".

# Usage
1. Point the ship in the direction you want to go
2. Bearing of 0/360 heads towards EOS (negative on the Z), 180 is out to the belt.(positive Z)
3. Angle of 0 is level with Z and X axis, angle of 90 will take you to the top of the belt while -90 will take you down to the bottom. 

# Note 
System only works while stationary

# License
GNU GPLv3

# Credits
https://github.com/xyberviri / Xyberviri#5609

https://github.com/Archaegeo / Archaegeo

LizardFish

Original code (https://github.com/Archaegeo/Starbase/blob/main/ISAN-Waypoint%20System/ShipHeading.yolol)
