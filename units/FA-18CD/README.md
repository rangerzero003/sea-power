# McDonnell Douglas F/A-18C/D

Kitbashed version of the F/A-18C/D using the Super Hornet mod from the Steam Workshop https://steamcommunity.com/sharedfiles/filedetails/?id=3426791311

This mod requires Sealifter to work properly. If you are having issues make sure that Sealifter is installed properly.

This also requires the Boeing F/A-18E/F Super Hornet mod to work. Ensure that the F/A-18C/D mod is above the F/A-18E/F mod in the mod manager, as this mod uses some of the files from the F/A-18 mod.

## Models

Model compliance CC 4.0
F/A-18E and E/A-18G source:
https://sketchfab.com/3d-models/mcdonnell-douglas-fa-18eboeing-ea-18g-growler-d69153c8e91744cab2bad239a2cb5d98

F/A-18F source:
https://sketchfab.com/3d-models/boeing-fa-18f-super-hornet-free-447caa975f5345 54a83f70f0877b73fb

## F/A-18C/D

While trying to find new aircraft to add to Sea Power, I came across Texas_the_Omertosa's Super Hornet mod. I wanted to use them in some scenarios that I was working on, but they didn't fit into the timeframe of the scenarios I was working on.

The original F/A-18A/B entered service in the early '80s, and the F/A-18C/D followed in the late '80s. This mod originally started as a F/A-18A/B mod, but most of the specifications I could find where for the C/D models, and from what I could tell, most squadrons transitioned directly to the C/D models, so the mod was condensed into the F/A-18C/D.

This mod is a kitbash of the F/A-18E/F mod, which means that it uses the Super Hornet model. I'm not a modeler so I wasn't able to alter the model, nor provide any textures. All squadrons use the default grey texture as well.

I removed the extra Air to Air pylon that the Super Hornet has on each wing, and modified some of the internal performance values to match what specifications I could find on the internet for the F/A-18C/D.

## New Units

Strike Fighters:
- F/A-18C
- F/A-18D
- CF-188A (Only the A model was added, as I couldn't find which squadrons flew the B model)

Weapons:
- AGM-65F Maverick

## Loadouts

F/A-18C/D (Used this PDF for DCS for loadouts: https://github.com/rangerzero003/sea-power/blob/main/units/FA-18CD/Loadout%20%26%20Weapons%20FA18C_v2.pdf)
- Default
-- 2x AIM-9L
-- 5x AIM-120C
-- 3x Fuel Tanks
- Ferry
-- 3x Fuel Tanks
- Air to Air
-- 6x AIM-9L
-- 5x AIM-120C
-- 1x Fuel Tank
- Air to Air Long Range
-- 2x AIM-9L
-- 5x AIM-120C
-- 3x Fuel Tank
- SEAD
-- 2x AIM-9L
-- 4x AGM-88 HARM
-- 1x AIM-120C
-- 1x Fuel Tank
- SEAD Long Range
-- 2x AIM-9L
-- 2x AGM-88 HARM
-- 1x AIM-120C
-- 3x Fuel Tank
- Anti-Ship
-- 2x AIM-9L
-- 4x AGM-84 Harpoon
-- 1x AIM-120C
-- 1x Fuel Tank
- Anti-Ship Long Range
-- 2x AIM-9L
-- 2x AGM-84 Harpoon
-- 1x AIM-120C
-- 3x Fuel Tank
- Strike
-- 2x AIM-9L
-- 8x Mk-82
-- 1x AIM-120C
-- 1x Fuel Tank
- Strike Long Range
-- 2x AIM-9L
-- 4x Mk-82
-- 1x AIM-120C
-- 3x Fuel Tank
- Strike Precision
-- 2x AIM-9L
-- 8x GBU-12
-- 1x AIM-120C
-- 1x Fuel Tank
- Strike Heavy
-- 2x AIM-9L
-- 4x Mk084
-- 1x AIM-120C
-- 1x Fuel Tank
- CAS
-- 2x AIM-9L
-- 4x GBU-12
-- 4x CBU-100 Rockeye
-- 1x AIM-120C
-- 1x Fuel Tank
- Anti-Armor
-- 2x AIM-9L
-- 4x AGM-65F Maverick
-- 1x AIM-120C
-- 1x Fuel Tank

CF-188A
Has all of the same loadouts as F/A-18C/D, except it does not have the Anti-Ship and Anti-Ship Long Range loadouts, and has a slight change to the CAS loadout
- CAS
-- 2x AIM-9L
-- 4x GBU-12
-- 2x Zuni Rocket Pods (Not the exact ones that the RCAF uses, but the closest I could get)
-- 1x AIM-120C
-- 1x Fuel Tank

## Squadrons

Mod contains all RCAF squadrons that flew the CF-188A, and the USMC and USN squadrons I could find that flew the F/A-18C/D. Every squadron has a callsign, as well as a nickname and their official designation. All of the USMC squadrons and about half the USN squadrons contain a small blurb in the Encyclopedia with the dates that they flew the F/A-18C/D, as well as home port and CVW cruises to help when creating realistic scenarios. I'll add the rest as I have time, and I plan to add other nations that flew this aircraft as well.

## Notes

AGM-65F:
I added the AGM-65f as a new weapon for this mod, as it was the version that I saw that the F/A-18C/D employed. It uses the vanilla AGM-65B model, but I modified the internal performance values to match the values I could find. The AGM-65F may be overpowered but I set the internal power value to about 2x as powerful as the AGM-65B due to this:

AGM-65B warhead: 57kg
AGM-65B internal power value: 23

AGM-65F warhead: 136kg

So 136/57 ~= 2.39, then 23 * 2.39 ~= 55

So the AGM-65F internal power value is 55.

All of the files that are in this mod are located here: https://github.com/rangerzero003/sea-power/tree/main/units/FA-18CD