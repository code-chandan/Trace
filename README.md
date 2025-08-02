# Trace, the CNC Router !
<img width="1200" height="500" alt="473084075-92e261d6-6934-49d6-86aa-f784dd4165f3" src="https://github.com/user-attachments/assets/25c9d8ad-760f-4a99-a863-ff3a931a5c32" />

<br>
<br>
<br>
<br>

<img width="3024" height="1316" alt="CNC_Render" src="https://github.com/user-attachments/assets/99533f64-736b-44bd-a09c-3b5cd120e6ea" />


Trace is a DIY CNC router that’s all about making CNC more accessible and fun. Built by chandan aka maverick hehe, it uses 3D-printed ABS parts to keep things strong but affordable. It’s got a decent working area, around 600 by 400 mm, which is big enough for wood, aluminum, brass, plexiglass, and even plastic. So whether you're carving, cutting, or doing some light metal work, it can handle it.

At the heart of it is the BIGTREETECH SKR 1.4 Turbo, and it runs on Marlin, which is super easy to use and gets the job done without any fuss. If you’re trying to learn how CNC machines work or just want something you can build and tweak yourself, Trace is perfect. The whole thing is designed to be assembled by hand, so you actually understand how it works while you build it.

| Image | Description |
|-------|-------------|
| <img width="3024" height="1316" alt="CNC_Render_Front" src="https://github.com/user-attachments/assets/222c6571-a2ca-4bde-9703-8bfd1c1e9591" /> | Front render|

| Image | Description |
|-------|-------------|
| <img width="3024" height="1316" alt="CNC_Render_Mis2" src="https://github.com/user-attachments/assets/bcdb3371-2e0d-48e9-ad8b-728c2cef95bd" /> | closeup render|

| Image | Description |
|-------|-------------|
| <img width="3024" height="1316" alt="CNC_Render_Mis" src="https://github.com/user-attachments/assets/de89e771-0b66-43dc-861e-ce98ae8b7edd" /> | closeup render|

| Image | Description |
|-------|-------------|
| <img width="3024" height="1316" alt="CNC_Render_Side" src="https://github.com/user-attachments/assets/bb1bb12c-0bd5-4a84-82e6-ca7c39a9756c" /> | side render |


# testing myself lol

So this is Trace, my attempt at designing a functional, affordable, and actually buildable CNC router. I haven’t built it yet this is just the design stage but it’s something I’ve been slowly putting together with the goal of making a CNC machine that doesn’t cost a fortune, actually works, and can be put together without a full machine shop or an engineering degree.

The idea behind Trace is to keep things modular and accessible while still being tough enough to machine actual materials like wood, aluminum, plastic, brass, and maybe even some light steel cuts if you go slow. The working area is around 600 x 400 mm, which I think is a pretty sweet size   not too tiny, but not massive either. Should be enough for most hobby projects, DIY parts, PCBs, signs, enclosures, etc.

I designed it around the BIGTREETECH SKR 1.4 Turbo because I wanted something reliable and easy to integrate, and I didn’t really feel like fighting with firmware bugs or weird driver issues. It’s not the cheapest route, but it makes up for that with stability, especially for people who want to actually use the thing instead of constantly fixing it.

The frame is all V-slot aluminum extrusion, and a good chunk of the parts are 3D printed in ABS. I went with ABS because it holds up better than PLA when things get hot, and it doesn’t warp like crazy if printed right. It also means you don’t need a CNC to build a CNC, which is kind of the whole point. I’ve kept the number of custom metal parts super low  like ideally just the spindle mount and maybe some plates you could laser cut or get fabricated.

The whole thing is meant to be pretty straightforward to assemble. I haven’t done the physical build yet, so I’m expecting some design tweaks when I finally get around to putting it together, but I’ve tried to avoid annoying alignment traps or impossible-to-tighten screws. The goal is for someone (including me) to print the parts, order the hardware, and actually get it working without rage quitting.

I’m sharing all the files under the MIT License, which basically means do whatever you want with it  use it, remix it, sell it, learn from it. Just don’t sue me if it sets your garage on fire or eats your hand or something. This is still untested hardware, so treat it like an alpha version of a machine. If you do build it, I’d love to hear what worked, what didn’t, and what broke immediately.

I’m still working on finalizing the BOM and doing a test build. Once that’s done, I’ll update this repo with real assembly instructions, wiring diagrams, and maybe some toolpaths or sample G-code. For now, it’s just the design files, notes, and a bunch of Fusion 360 screenshots.

More soon. This is going to be fun.

# BOM
| Part                          | Price per Unit (INR) | Quantity | Total Price (INR) | Total Price (USD) | Link                                                                                   |
|-------------------------------|----------------------|----------|-------------------|-------------------|----------------------------------------------------------------------------------------|
| MGN15H Linear Rails           | ₹899                 | 6        | ₹5394             | $62.72            | [novo3d](https://novo3d.in/mgn15h-linear-rail/)                                        |
| NEMA 23 Stepper Motors        | ₹1199                | 4        | ₹4796             | $55.77            | [robocraze](https://robocraze.com/products/23hs5628-nema23-stepper-motor?variant=40193193214105) |
| BIGTREETECH SKR 1.4 Board     | ₹3699                | 1        | ₹3699             | $43.01            | [novo3d](https://novo3d.in/bigtreetech-pi-v1-2-control-board/)                         |
| Ballscrews                   | —                    | —        | ₹0                | $—                | Already available                                                                      |
| Spindle Clamp                | —                    | —        | ₹0                | $—                | Already available                                                                      |
| Aluminum Components          | —                    | —        | ₹0                | $—                | Already available                                                                      |
| IoT Switching Relay Power Strip | —                 | —        | ₹0                | $—                | Already available                                                                      |
| 24V Meanwell Power Supply    | ₹1204                | 1        | ₹1204             | $14.00            | [amazon](https://amzn.in/d/6Mayd64)                                                    |
| Router / Spindle             | ₹4000                | 1        | ₹4000             | $46.51            | —                                                                                      |
| Fasteners                    | —                    | —        | ₹0                | $—                | Got a box full at home                                                                 |
| 3D Prints                    | ₹949                 | 1        | ₹949              | $11.03            | [amazon](https://amzn.in/d/5rqDBXf)                                                    |


total : $223
**Note:** Some components like the spindle clamp, aluminum plates, and ballscrews were already available and not included in the final cost.
