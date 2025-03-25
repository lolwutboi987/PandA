# PandA RPD 
 The Portable and Automated Rapid Protyping Device
 
 Made by @lolwutboi987
 Total Hours on CAD: 15
 Total Hours on BOM: 2
 Total hours on Git Repo: 2
 # 3/18/25, Day 0: The brainstorm
 It was a boring tuesday afternoon. I had nothing to do, and was chatting with my group after the absolute chaos that was scrapyard silicon valley. I was chatting on discord about how it was funny that we brought a 3d printer to the hackathon, untill my friend mentions the infill channel. I browse through the channel, excited for another engineering related thing to do during the vex offseason. One problem: Where do I begin? With Scrapyard SV still on my mind, I think of my ender 3 that we brought and the numerous problems that arised when it came to taking a conventional 3d pritner with you on the go. I decided, Why not make a 3d printer designed for hackathons? (Or any situation that requires rapid protyping). Here's what would make a printer optimal in this scenario:

 - Optimized velocity for high speed printing.
 - Minized downtime to allow maximum throughput of prototyped parts.
 - Maximum convenience means reducing hassle with the printer, and increasing time for working/printing.
 - Portability means that said printer can be taken anywhere conveniently.
## Notes
And so the day ends. With a general idea of what my plans are for this project, I've got 13 days to make it work so i will begin to CAD tommorrow. 

# 3/19/25, Day 1: Cadding Framework
## Creating the file:
With profound experience with both, I am offered both OnShape and Fusion 360 for this project. As this will be a primarily top-down designed project, and online collaboration wont be an absolute requirement, I have chosen Fusion 360. 
## The frame:
Every good printer design starts with a frame. It lays the constraints and framework (hehe) for the motion systems and gives a general idea of the printer's design. For maximum compactibility, I have decided on a Cantilever frame.

![image](https://github.com/user-attachments/assets/9205c7f6-5371-4150-8917-4b5e247e0315)

The Z axis bar is removable, allowing for easy folding of the PandA.
## The Y axis
I have also been able to complete the Y axis. 

![image](https://github.com/user-attachments/assets/c8978fe5-faf1-4eff-a5c0-21da630e701a)

The Y axis incorporates a beefy 42-48 Stepper for maximum torque and velocity. The Bed frame and the Hotbed itself are both carbon fiber. Carbon fiber's Strength-to-weight ratio, stiffness, and relative price point makes it optimal for this situation. 

The Y axis slides upon a nice and extremely thick MGN15H carriage as it's undoubtedly the heaviest moving part on the printer. This size of rail means that wear and friction will be reduced. 

![image](https://github.com/user-attachments/assets/7baa51e6-7288-45c7-b4a5-43c3a1b1fd3f)

The beltpath is drawn in an indigo-blue.
You might be wondering, why would someone do such a beltpath? This is once again, to optimize form factor and simplicity. 

One might also wonder, Why the object circled in red exists. it's there to once again, guide the belt through the 4020 Extrusion without the need for a larger drive pulley which would otherwise, sacrifice torque and performance. 


