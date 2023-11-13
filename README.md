# Sunscreen
Sunscreen-Awning project for Home Assistant.

This is part of my own documentation and also to inspire people. 
I hope it's usefull for others and improvements can be made for sure :). 

A brief description of the working:
All threshold values can be giving in a lovelace card and stored in input helpers.
Every minute a automation checks if actual weather values met the given conditions and awkning would be controlled.
as extra notifications would send and all helpers and actual data is also stored on google sheets to debug, dry run methode to improve values.
<image src="https://github.com/remb0/Sunscreen/blob/main/screenshots/lovelace%20conditions.png?raw=true"></image>
<image src="https://github.com/remb0/Sunscreen/blob/main/screenshots/set%20lovelace.png?raw=true"></image>

## This repo:
#### helpers and sensors
https://github.com/remb0/Sunscreen/blob/main/Sensors-Helpers

#### 1 automation
https://github.com/remb0/Sunscreen/blob/main/automation.yaml

#### lovelace card(s)
https://github.com/remb0/Sunscreen/blob/main/lovelace



# Link to other projects:
ESPSomfy-RTS <image src="https://user-images.githubusercontent.com/47839015/218898940-3541b360-5c49-4e38-a918-392cd0408b76.png" style="width:177px;display:inline-block;float:right"></image>
https://github.com/rstrouse/ESPSomfy-RTS

# Whishes / ToDo:
- dry run (fake) with actionable notifications on telephone
- translate all helpers to englisch
- manual overide option
- notifications on telephone why the screen is moving (screen is going up because of exspected rain)
- smaller lovelace design
