---
title: "North Pole"
author: "1Mon"
description: "1Mon's Tiny Polar Printer"
created_at: "2025-07-26"
---

# Total Time Spent: 18h

# Frame Design

In this first session I began desigining the frame for the polar printer. Its currently very small (230x180) and is made out of 2040 and 4040 extrusions, making it very rigid and stable. Im planning to mount an aluminum plate to the top of it, both for mounting the bed and its motor, but also to contribute to the rigidity. I plan to use a slipring in the bed so its able to rotate forever, without worrying about wires. I need this for the bed heater and thermistor. The frame is built with a rectangle of 2040, with one side as 4040 to allow the z axis extrusion to mount properly. Im also going to be mounting the Z motor to this extrusion, so its very important for it to be rigid. I played around with the size of components a lot to make it a reasonable size for the 120mm bed, but this size I've landed on seems like a really good balance between compactness and having enough space for electronics and other parts. 

<img width="523" height="532" alt="image" src="https://github.com/user-attachments/assets/ba81accf-a8b3-4b1d-96a6-8f6569fadcf9" />

Here you can see the frame of the printer. 

**Time Spent: 3h**

# Bed system

During this session I began desigining the bed system. This includes the mounting on a bearing, and the belting to connect it to the motor. So far I have just added the bearing, which is clamped between two printed parts. M5 bolts will go through the part, the aluminum plate, and the other clamp on the bottom. This should keep the bearing very well constrained and stable, which should lead to the actual bed being very stable. I still need to figure out the actual bed mounting, as I currently dont have anything. I also added the aluminum plate in this session, which mounts the bearing as well as the motor and bearing. 

<img width="818" height="542" alt="image" src="https://github.com/user-attachments/assets/9411e340-a172-408c-b5dd-634b59793afe" />

current design

<img height="319" alt="image" src="https://github.com/user-attachments/assets/9bd9ddf5-731b-42a4-b30e-303ae0b96e2a" />

Cross section of the bearing mounted

**Time Spent: 2h**

# dummy bed + z axis

In this session I designed a dummy bed for sizing purposes and for testing the belt system. The bed is super bare bones (literally just two cylendars), but it should be a decent representation of what I need to make next. In this session I mainly worked on the Z axis, which is basically a 150mm leadscrew stepper motor connected to a mgn12 carriage. I still need to make it more rigid, but it should be a decent option. The Z carriage is also where the X axis (or realy Rho) rail will be mounted, so it needs to be super sturdy. I may end up adding a second rail to give it more rigidity, but since its such a small design its probably not needed. 

<img width="385" height="747" alt="image" src="https://github.com/user-attachments/assets/56601e71-6747-43b5-90af-f3d9eb1d227e" />

Here you can see the first prototype of the z axis. Im pretty happy with the motor mount but im not sure about the carriage. Its very thin in its current state, which means that its not very rigid. 

<img width="893" height="695" alt="image" src="https://github.com/user-attachments/assets/ef96ecb7-017b-4d87-869f-108e83fa712d" />

And here is the dummy bed. I might end up just doing kapton tape so I dont need to worry about running high current through a slipring. 

**Time Spent: 2h**

# Bad CAD!!

I woke up and realized how bad the x (rho) axis motor mount is so I spent some time making it beefier I make it more of a solid block instead of plates, and aligned the pulley better to work with the toolhead. Its much beefier now, and should be able to hold up better to the forces from the motor. I still need to reinforce the X (rho) linear rod, as the current mounting solution is pretty sketchy and probably wont be very rigid. I had to move some stuff around to allow for clearance for the leadscrew and belts, but once I got that sorted it was fairly easy to add the beefy part. This mounting solution also lets me use some very large m3 bolts to sandwich all of the components together. 

<img width="855" height="479" alt="image" src="https://github.com/user-attachments/assets/fcae2c07-6cc9-4420-97b8-dfc7eca486cb" />

I also realized that it is going to be very difficult to tension the bed pulley well, so I added a slider to let the motor and pulley move further away from the bed, tensioning the belt loop. I also added the bed pulley, which is a commonly available 80t gt2 pulley. Its press fit into a large bed spinner, which will end up being the print surface. I plan to use kapton tape to get parts to stick to the bed, as it is cheap and holds onto PLA fairly well. This greatly simplifies wiring this printer, as I dont need to worry about any sliprings or expensive components for the heated bed. I was inspired by Kappy by rolohaun for this, as it is a primary feature the low cost bedslinger. 

<img width="514" height="374" alt="image" src="https://github.com/user-attachments/assets/32eec2a2-932f-411b-8627-babfe0069f3d" />

Here you can see the layout under the printer. The motor has 10mm of movement on its tensioner, which should be plenty for what I am trying to do. 

<img width="982" height="369" alt="image" src="https://github.com/user-attachments/assets/dd3ccd71-0ac0-4cea-b049-e6577f6237de" />

And here you can see how the belt will connect. The large gray pulley connected to the bed is 80t, and the smaller one connected to the motor is 20. 

**Time Spent: 4h**

# Toolhead Design

I spent way too much time working on this toolhead. It was the hardest part of this design by far. It uses a TZ V6 hotend, which is like a bambu heater connected to a v6 heatsink, because it is cheap and readily accessible on Aliexpress or Amazon. It uses a 2510 fan for hotend cooling, as well as a 4010 blower fan for part cooling. It is mounted on a mgn9h rail, as a balance between rigidity and size. I am running a bowden system for this toolhead, as the cantilever design means that having a heavy toolhead will lead to slop and issues. My belt mounting system is fairly simple, just a slot on the back of the toolhead which allows both sides of the belt to connect and move the toolhead around. I dont have much experience designing toolheads, so this is just the way I am thinking through it. 

<img width="861" height="637" alt="image" src="https://github.com/user-attachments/assets/67760dfb-5dcb-4615-9df9-0522458386bb" />

The main part of the toolhead is a single print. I intend to print this out of PA6 CF, for rigidity and temp resistance. 

<img width="847" height="610" alt="image" src="https://github.com/user-attachments/assets/82499afb-8a59-4479-97b7-ef3eb90a1e64" />

Here is the current state of the toolhead design. Im not super happy with how it looks currently, but Im sure it will change over the next could sessions. The good thing is that it is very simple and light, which means that performance should be fairly good.

**Time Spent: 4h**

# Final Motion Components

In this session I added the X Idler and the extruder to the printer. For the idler, I mounted it directly to the rail, which helps align it to the belt path. I am using a 20t idler for this, as it matches the pulley on the other side. This is important because I want equal force pulling on each side of the toolhead. For the extruder, I chose an HGX Lite. This is a clone of the very popular LGX lite, using big gears for high grip and an aluminum body for rigidity. I mounted this to the X/Z carriage, as letting it move with the toolhead means less strain on the bowden. 

<img width="423" height="450" alt="image" src="https://github.com/user-attachments/assets/74298afa-c2bc-4f1b-b94a-9228c7f9c2b5" />

Here you can see the extruder, mounted sideways for compactness. There will be a bowden tube going from it to the toolhead. 

<img width="544" height="686" alt="image" src="https://github.com/user-attachments/assets/ac53f05c-ccfd-4b0c-88cd-6281ae36cde5" />

And here is the X idler. Its pretty simple and compact as I wanted to keep the weight down on the far end of the cantilever. 

**Time Spent: 3h**
