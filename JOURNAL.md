---
title: "North Pole"
author: "1Mon"
description: "1Mon's Tiny Polar Printer"
created_at: "2025-07-26"
---

# Total Time Spent: 7h

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
