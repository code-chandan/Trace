# Hours spent ~50 hours


# day 1
time spent: 2.5 hours

Kicked things off by just dumping all the ideas in my head into a Notion page. Looked at a few random DIY CNC builds online to figure out what size I’m even aiming for. Nothing too crazy, just something that can eat through MDF and acrylic for now. Got kinda obsessed with the linear rail options but didn’t finalize anything yet. Honestly just trying to wrap my head around motion systems and how all the axes are gonna move without interfering with each other.

# day 2
time spent: 1.5 hours

Spent time learning about frame types. V-slot, T-slot, aluminum extrusion, MDF base? So many choices. Dug through a few Reddit posts and tried making a rough layout sketch on paper. Thought I had a plan until I realized I didn’t account for the Z height. That’s tomorrow’s problem.

# day 3
time spent: 3 hours

Jumped into Fusion 360 today. Made a basic frame with 2040 extrusions. Started modeling a gantry just to see how awkward it’s gonna get. Spoiler: very awkward. Couldn’t figure out how to mount the spindle without it hitting the Y rails. Going back to the drawing board tomorrow. Probably going to mock it flat before I go full 3D again.

# day 4
time spent: 2 hours

Watched some guy on YouTube model an entire CNC router in 12 minutes. It gave me false hope. Tried doing the same thing and ended up with a crooked Z axis and missing fasteners. At least I know how joints and constraints work now. Still stuck choosing between belt drive and lead screw.

# day 5
time spent: 3 hours

Made some progress figuring out the Y axis. Tried lead screw first, but belt drive feels simpler and cheaper to maintain. Modeled both to compare them. Belt drive looks cleaner and gives more space under the gantry. Think I’ll go with that. Might regret it later but we move.

# day 6
time spent: 2.5 hours

Started designing the carriage system. Realized I’d been avoiding the Z axis this whole time. Looked at a few openbuilds designs and tried to copy their vibe. Got stuck again on how to mount the spindle in a way that won’t flex like crazy. Thinking I might need to buy a prefabricated Z module.

# day 7
time spent: 2 hours

Kinda just stared at Fusion today. Did some minor tweaks, changed the position of the motors, and tested how much clearance I’d get if I increased the Z height. Noticed I forgot to leave space for wiring and drag chains. That’s gonna need a whole new pass soon.

# day 8
time spent: 2.5 hours

Started laying out electronics. Made basic placeholders for the stepper motors, drivers, and power supply. Thinking about putting everything in a side-mounted control box. Also realized I have no idea how to design a good cable management system. Might 3D print clips or use some aluminum brackets.

# day 9
time spent: 1.5 hours

Looked at options for limit switches and emergency stop buttons. Modeled a tiny bracket to hold a limit switch near the gantry but forgot about travel clearance. Also spent too much time deciding whether I want the control box on the left or right side. No clue why that decision took 30 minutes.

# day 10
time spent: 2 hours

Did another clean-up pass of the whole design. Things are starting to actually look like a CNC router now. Still needs a lot of alignment checking and sanity checks before I start thinking about manufacturing. Might export a few drawings to plan the baseplate.

# day 11
time spent: 2.5 hours

Started messing with the base design. Decided to go with an MDF sacrificial layer on top of a plywood base. Had to rework the frame slightly to support it properly. Also added some mock T-nuts and hold-downs just for the visual. Looks way cooler now even though none of it’s real yet.

# day 12
time spent: 1.5 hours

Tried doing some stress tests in Fusion but I don’t trust my results at all. My joints are too loose and the simulation crashes half the time. Will probably just build it and hope for the best. Also started compiling a rough BOM. Stepper motor prices are all over the place.

# day 13
time spent: 3 hours

Redid the Z axis again. This is probably the third time but it finally feels solid. Made a proper mounting plate for the spindle and gave it some depth so I can add a dust shoe later. Still not sure how I’ll secure that though. Might leave it detachable for now.

# day 14
time spent: 2 hours

Got serious about the gantry. Made the sides taller so the X rail sits higher, giving me more travel below. Had to shift the motor mounts again and double check belt clearance. I think the layout is solid now. No obvious crashes between components.

# day 15
time spent: 2.5 hours

Did a huge cleanup today. Renamed all my components, organized them into folders, and made a proper assembly. Fixed the origin point too so everything’s easier to measure from now on. Feels way easier to work with now. Should’ve done this from day 1.

# day 16
time spent: 2 hours

Added an enclosure idea just for fun. Might never actually build it but it looks super clean in the renders. Gave it a clear top and a front-opening hatch. Still need to think about airflow and chip collection but that’s way later. Right now it’s just vibes.

# day 17
time spent: 2 hours

Finalized the mounting holes and baseplate. Took a while to align everything with the spoilboard slots. Marked drill holes for mounting the motors and lead screw nuts. Exported a few DXFs and test printed one on paper to check scale. Pretty hype.

# day 18
time spent: 2 hours

Made a wiring diagram today. It’s ugly but it works. Routed wires from the motors to the control box and marked where the power supply and relay module will go. Planning to add some ferrules and wire labels later when I build. This part was way more fun than I expected.

# day 19
time spent: 2 hours

Started building a fake BOM to prep for sourcing. Listed rails, motors, belts, PSU, control board, etc. Prices are all over the place and half the links are dead but it gives me a rough idea of cost. Definitely not cheap but not as insane as I thought. Maybe around 12-15k INR.

# day 20
time spent: 2.5 hours

Final check of the whole design. Rotated every part, checked fitment, did a dry run through the motion system in Fusion. It’s actually moving the way it should. Saved backups of the full design, BOM, and wiring stuff. Ready to move into manufacturing next.
