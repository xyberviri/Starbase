![Material Scanner Output](Material_scanner.jpg)
# Material Scanner Script
This script automates the usage of the Material-Point-Scanner.

# Setup
1. Have a Material-Scanner attached to your ship and properly wired up, with default field-names.
2. Have a Button of type 1, with it's ButtonState-Field renamed to "Active".
3. Have a text-panel with it's field renamed to "\_Scan\_"

# Usage
1. Press the "Active"-Button. The Scanner is now on and will continously try to scan (until you re-press the button).
2. Aim the scanner at an asteroid
3. The scanner will now scan the asteroid, print it's content on the text-panel along with how many slots the materials will take. 

# Note 
Slot size is based on volume, the scan is reporting 1712 while the ingame volume for a block of ore is reported as 1728 on the in game display. 

# License
MIT

# Credits
https://github.com/xyberviri Xyberviri#5609

https://github.com/dbaumgarten / dbaumgarten#9279
