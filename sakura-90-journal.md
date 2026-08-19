# Sakura 90

A mechanical keyboard with 88 keys, a rotary encoder and a sakura theme.

# 2026-08-19: More Rejection Problems

**Total time spent: 45 mins**

Tried to fix the problems in the design, also made some more adjustments to the 3D files and the PCB.
![image.png](https://cdn.hackclub.com/01a01aec-923d-78c7-977a-9337bf91e5f4/image.png)

# 2026-08-19: Rejection Problems

**Total time spent: 1 hour**

I've tried to fix the problems with the design and the repo because it rejected. I organized the files, added more pictures and fixed the BOM formatting issues.
![image.png](https://cdn.hackclub.com/01a01aec-401b-7071-aa93-cc854a289d91/image.png)

# 2026-08-19: Github Repo

**Total time spent: 2.5 hours**

Today I finished the repository in Github. The readme has a small intro to the project along with a picture and a BOM in table form. There are also all the KiCad files used, along with the BOM in csv format, gerber file and 3D files in both step and stl formats.
![image.png](https://cdn.hackclub.com/01a01aeb-8a5e-76f5-8d04-9cab89cf2413/image.png)

# 2026-08-19: Scenery

**Total time spent: 1.5 hours**

I thought a plain white build would look a bit boring so I decided to add a sakura landscape. I spent literally ages trying find image to use as a DXF but they were all too big and the wrong format. I tried converting them but they still ended up too big. In the end I decided to make my own so I started adding the lines on the surface in a sketch to make 2 mountains, a cherry blossom branch and 2 patches of grass coming in from either side. I then offset them by 0.1mm and extruded them downwards and then extruded the un-offset shape in the sketch to make a flat piece of colored plastic that I could just superglue in.
![image.png](https://cdn.hackclub.com/01a01aea-d92a-72fb-859f-8fa024bf904e/image.png)

# 2026-08-19: Border Design

**Total time spent: 45 mins**

Since exposing the switches would look a bit crappy I decided to add a border that covers them up. I calculated the edges and width of the borders. I tried to loft it up using the loft tool but that did not work so I extruded the outline and then chamfered the edges. I also added the holes for the threaded inserts.
![image.png](https://cdn.hackclub.com/01a01aea-305a-7cfc-a1b4-37d1b903b32e/image.png)

# 2026-08-19: Plate Design

**Total time spent: 15 mins**

The plate did not take as long as the case because all I had to do was import the DXF from AI03 Plate Generator and extrude it to 1.6mm. Then I extruded the borders to match the base and then chamfered the corners. I also added a square hole for the rotary encoder and more M3 screwholes.
![image.png](https://cdn.hackclub.com/01a01ae9-13ca-7843-90b5-db2f8267ff92/image.png)

# 2026-08-19: Base Design

**Total time spent: 4.5 hours**

In this session I designed the bottom case or base for the keyboard. I has a 5 degree typing angle and the PCB is mounted using tabs and screws. I started by importing the PCB .step file in to Fusion 360 and then offsetting the PCB outline. I then offset that and made the walls. I then created a direct lip all around the inside of the case like a ledge to help hold the PCB. I also helped to hold the PCB using projections that slot into the holes on the bottom of the PCB. I then added slots for the USBC daughterboard. Then came the screw holes and the holes for the metal rods that help hold the 3 parts of the case. I had to do it like that because the person who 3D prints my parts only has a 180mm cubed print bed.
![image.png](https://cdn.hackclub.com/01a01ae7-ab0c-7887-a64d-94eea4c27914/image.png)
![image.png](https://cdn.hackclub.com/01a01ae7-ed7d-71f2-ad21-b4c0b19105e8/image.png)

# 2026-08-19: Plate as a DXF

**Total time spent: 30 mins**

I spent sometime creating the layout in a the keyboard layout editor and exported the dxf in the ai03 plate generator. This was because it wouldn't let me export the plate file as a step file in KiCad because of tolerance issues that couldn't seem to be solved.
![image.png](https://cdn.hackclub.com/01a01ae6-64a8-7747-856a-3641f5ec4dd9/image.png)
![image.png](https://cdn.hackclub.com/01a01ae6-8956-7ad6-9125-c570ea3b74e1/image.png)
![image.png](https://cdn.hackclub.com/01a01ae6-a729-7211-a84e-11033b0ba55d/image.png)

# 2026-08-19: Plate

**Total time spent: 3 hours**

I created another PCB planning it to be the plate coloured white and to be made of FR-4. I added in the footprints directly from the PCB editor, while making the position of the switch cutouts match the position of the switches match the actual PCB. Then I realised that making the plate as a PCB would be too expense and decided to export the plate as a .step straight from KiCad to design the case.
![image.png](https://cdn.hackclub.com/01a01ae5-4af6-7027-b3d1-6480f213bf42/image.png)

# 2026-08-19: PCB

**Total time spent: 4 hours**

Managed to finish the entre PCB in one sitting. I started by arranging all the key switches using the position relative to item tool, while making stupidly extensive calculations on paper from the misshapen keys. Once I had placed all the keys and rotary encoder, I wired the entire PCB. After that, I just happened to realize the there would be no space for the chip and if I place it anywhere else it would look really awkward and out of place so I had to rearrange the keys and delete some of the wiring, place the chip, and then wire the section over again. Then I placed the mounting holes and the edge cuts while adding slot cutouts to support it against the plate while placing the key switches.
![image.png](https://cdn.hackclub.com/01a01ae4-9448-79cf-bc63-d1e3bd42a1e6/image.png)

# 2026-08-19: Schematics

**Total time spent: 3 hours**

I did some research into the ESP32 S3C1 N16R8 chip and its data pins. I'm using an ANSI 80%. I wired all the parts and roughly arranged them in the layout I want for the PCB. Then I assigned all the footprints one by one according the layout and order of parts.
![image.png](https://cdn.hackclub.com/01a01ae3-137a-7925-8fec-3f4f4f75e0eb/image.png)
![image.png](https://cdn.hackclub.com/01a01ae3-2adb-79bb-8284-cf7d02ecc867/image.png)

