# Hours spent ~25 hours


# day 1
time spent: 1.5 hours ( made notes of each and everything, tryna understand everything at every point, thus the 1.5 hours)

<img width="400" height="1202" alt="image" src="https://github.com/user-attachments/assets/d1433caf-3eca-4b98-9c43-6b6afa0941cc" /> <img width="400" height="1201" alt="image" src="https://github.com/user-attachments/assets/2f22036b-dc48-4499-8696-2d637e9a3781" />

1.[What is CNC Router & How Does it Work?](https://www.youtube.com/watch?v=zd29RG5vqqo) , [Wattsan](https://www.youtube.com/@Wattsan)
A very useful breakdown of professional CNC routers was provided in this video. The most important lesson I learned was the importance of precise clamping and workholding setups, which I was somewhat winging. I also observed how they use drag chains to neatly route cables. I might have to take that into account for my own build in order to prevent snagged or messy wiring.
<br>
2. [Making a DIY CNC machine with limited tools](https://www.youtube.com/watch?v=covhU4L5N5g) , [Ben Makes Everything](https://www.youtube.com/@benmakeseverything)
This was a good illustration of how to remove CNC machine parts using only simple tools. I appreciated how he used a basic drill press and a lot of perseverance to mill out an extremely clean Z-axis plate. It served as a reminder that all I need to create solid parts is accuracy and a little forethought, not fancy equipment. It also inspired me to simplify some of my own bracket designs.


# day2 
time spent: 2 hours
<br>
<img width="440" height="2160" alt="image" src="https://github.com/user-attachments/assets/69f9fc45-d7e8-4a46-ac75-9761dd9545f3" /> <img width="440" height="2160" alt="image" src="https://github.com/user-attachments/assets/67fcdbe2-86dd-4f46-81d4-2d47af8cf548" />

I spent about two hours today studying the circuit diagrams that Ben shared in order to comprehend the wiring configuration and the arrangement of the parts in his CNC printer. In order to understand how the electronics were arranged in his design, I also opened and looked through the.f3z Fusion 360 files he sent. The primary goals of this session were to collect ideas and gain a better grasp of how everything works together. Even though my final circuit will be custom-built, looking over Ben's setup helped me better visualize what works and what to look out for when it comes to cable routing and board placement.

<img width="2000" height="1000" alt="image" src="https://github.com/user-attachments/assets/1dcec054-b588-43a5-bd1f-df9b0ac4c440" />

# [Ben's Github Repo](https://github.com/BenMakesEverything/Ben_CNC_v1)



# day 3
time spent: 2 hours
<br>
Designing the CNC router's base frame in Fusion 360 took me roughly two hours. Ten 2020 extrusions run horizontally between two 4080 aluminum extrusions positioned vertically on either side of the structure. The 4080s are the main supports and will likely carry the X-axis components later. In order to accommodate future linear rail or bracket mounting, I made sure the grooves faced inward. The 2020s are evenly spaced to create a sturdy platform base that provides sufficient surface coverage and strength for mounting the spoilboard.The modeling procedure was fairly simple: the profiles were primarily sketched, extruded to the proper lengths, and everything was precisely positioned using the align and joint tools.  In order to adjust the spacing or extrusion lengths later if necessary, I kept the design parametric.

| Image | Description |
|-------|-------------|
| <img width="1374" height="805" alt="Screenshot 2025-08-05 143159" src="https://github.com/user-attachments/assets/026ed4e2-c72d-47b1-be1e-e5b301e53aeb" /> | base of the router |


# day 4
time spent: 4 hours

I expanded the CNC router model for roughly three hours today.  I added the spindle mount, linear rails on all three axes, and the complete gantry setup. The gantry is now supported by a set of linear blocks and is constructed from twin 2020 extrusions on the X-axis.  Directly mounted linear rails allow the Y-axis to travel along 4080 extrusions. In order to preserve travel alignment and spacing, I carefully modeled and placed the rail blocks. A spindle holder and a vertical rail are part of the Z-axis. I made the mount to accommodate a small spindle with a simple housing by reusing 2020 for the Z-frame. Although it's not final, it currently works for scale and placement. Due to the numerous components and alignments, the assembly took a long time. particularly ensuring that the rail carriages did not interfere with mounting plates and sat flush.  However, now that everything is appropriately constrained, the structure appears mechanically sound for mockup or simulation purposes.

| Image | Description |
|-------|-------------|
| <img width="1254" height="701" alt="Screenshot 2025-08-05 183233" src="https://github.com/user-attachments/assets/e9cede5d-0479-4b80-880e-3efa190c8f26" /> | Gantry, Linear Rails, and Spindle Assembly |


# day 5
time spent: 2.5 hours

Today, the structural side plates and motor mounts for the Y-axis were added. The motion system is fastened to the base by the large aluminum profiles that are visible at both ends of the gantry.I created unique side plates to secure the motor and Y-axis lead screw. These are attached straight to the ends of the gantry and the linear rail carriage. The plates are shaped to preserve both rigidity and clearance, and they have mounting holes for pulleys and motor brackets.The majority of the time spent on this update was spent correctly sketching and constraining the plates. In order to guarantee alignment with the spindle and base board, I also made some adjustments to the Y-axis extrusions.Though structurally significant, it's a smaller step. The model is almost ready for machining volume estimation and full-axis movement simulation.

| Image | Description |
|-------|-------------|
| <img width="1438" height="730" alt="Screenshot 2025-08-05 184021" src="https://github.com/user-attachments/assets/b2a8148c-6d46-457a-8748-adf49ab0e202" /> |  Gantry, Y-Axis Motor Mounts and Structural Plates |

# day 6
time spent: 3.5 hours

The NEMA 23 motor on the Z-axis spindle mount is now part of the updated design. In addition, I installed the motor coupler, belt/pulley housing, and any structural supports required to connect the motor to the spindle plate. A detailed model of the Makita RT0700 has now taken the place of the placeholder spindle. For size, mounting holes, and clearance checks around the Z-axis, this offers a more accurate reference.Both Y-axis ends also received end-stop brackets. These blocks will be used as mounting locations for sensors or as mechanical boundaries. They also aid in completing the external framework.A more comprehensive mechanical layout, complete with motion components and a spindle ready for production, is now reflected in the model. 

| Image | Description |
|-------|-------------|
|<img width="1257" height="640" alt="Screenshot 2025-08-05 184644" src="https://github.com/user-attachments/assets/65718fc1-2103-476a-902e-94e240dcc077" /> | Motor Assembly, End Brackets, and RT0700 Spindle |


# day 7
time spent: 3.5 hours

The machine bed and motion control were the main topics of discussion today. Two on the Y-axis sides and one on each of the X and Z axes are the stepper motors that I added to all three axes. To get everything aligned, this required adjusting the coupling brackets, motor mounts, and some constraints.On both Y-axes, the lead screw system was installed. It comes with supported end blocks, anti-backlash nuts, and motor-side brackets. This gives the motion system a much more comprehensive visual feel. Additionally, I completed the Z-axis motor mounting on top.installed a slotted aluminum extrusion bed in place of the wooden baseboard. This modification makes the model more like the real machine in terms of appearance and operation.Additionally, it provides a clearer picture of clearances and the potential future functionality of clamping.

| Image | Description |
|-------|-------------|
|<img width="1431" height="676" alt="Screenshot 2025-08-05 185419" src="https://github.com/user-attachments/assets/00dc5cc4-3a87-4266-954b-091db3776c39" /> | Motor Assembly, End Brackets, and RT0700 Spindle |

# day 8

