---
title: "Recommissioning a Magneto-Optical Trap"
excerpt: "Bringing a cold-atom experiment back online after eight years of dormancy."
collection: portfolio
---

*Physics Advanced Instructional Lab, UC Berkeley — 2025*

---

A magneto-optical trap (MOT) uses carefully tuned laser beams and a magnetic field gradient to slow and trap neutral atoms, cooling them to temperatures within a fraction of a degree of absolute zero. The MOT in Berkeley's advanced instructional lab had not been operational for eight years when I took on the project of bringing it back online.

---

## Process

**Laser system.** The existing laser had failed (dead piezo). I sourced and installed a replacement laser, then did extensive realignment of the whole beam path. I also upgraded the laser controller, allowing for more stable laser locking/more stable MOTs.

**Laser locking.** The laser locking strategy needed to be revamped for the new laser. This was extensively documented, and I'm also working on better characterizing the transfer function of the system with the new laser/laser controller so that we can build a new lockbox better suited to the new laser (which only has temp/current control, no piezo) - hopefully this will lead to even better MOTs! 

**Control software.** The existing LabVIEW control software and Firewire camera only ran on Windows 7. In deference to our long-suffering IT department, the camera is being upgraded to a newer USB camera and the software rewritten in Python so the whole system can be upgraded to Windows 11.

**Documentation.** So much documentation! One of the big challenges was the relatively minimal documentation of the old system, so hopefully the design choices I made in the upgrades will be more clear to future users now. (Students have found the main lab manual reasonably usable so far, so success!)

---

## Media

<!-- ![Trapped atom cloud fluorescence](/images/mot_cloud.jpg) -->
<!-- *Caption: Fluorescence image of trapped rubidium atoms* -->

![MOT room](/images/mot_room.jpg)

*The MOT room is probably the most dramatic/cool looking room in the lab.*

<video width="100%" controls>
   <source src="/files/mot_demo.MOV" type="video/mp4">
</video>

*Successful MOT dropping and being recaptured!*

---

## Why It Matters

As of January 2025, the experiment is operational for the first time in 8 years, and is allowing students to work on a system central to AMO physics. (A student told me after doing the experiment this semester this confirmed they wanted to go into AMO physics!)