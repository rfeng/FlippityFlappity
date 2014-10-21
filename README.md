FlippityFlappity
================

Eric O'Neill<br>
Rundong Kevin Tian<br>
Ryan Feng<br>

EECS 149/249A Fall 2014
Final Project

Overview: The goal of our project is to design and prototype an expressive, interactive fish toy that reacts to movement and touch with color and motion.  <br>
<br>
Approach: We will outfit this Ikea pillow (http://www.ikea.com/au/en/catalog/products/60268326/) with sensors (capacitive touch, accelerometer, IR proximity) and actuators (a string of neopixels, an actuated spine using servos) to create interesting interactive behaviors. The main hardware system for the project is the mechanical spine, to be prototyped using laser cutters, 3D printers, and other rapid prototyping equipment.  The capacitive touch sensors are implemented as an array of open ended wires with an mbed capsense library.  As a stretch goal, we want to have this fish move around on the ground (‘walking’) using its actuated spine. <br>
<br>
Major Deliverables: A stuffed toy fish that can interact with its environment, (1) Actuation with Neopixel lights and a flexible spine, (2) Responsive to touch (capacitive sensors), and proximity (IR detectors) (3) behavior governed by a FSM, (4) Stretch goal: walking using its flexible spine<br>
<br>
Schedule: <br>
Week 1 (Oct 20 - 25): Project charter, FSM for fish behavior, finalize parts list, brainstorm 1st revision of mechanical design (CAD files production ready over weekend).<br>
Week 2 (Oct 27 - Nov 1): 1st mechanical prototype fabbed (laser cutting and 3d printing to quickly iterate). Prototype custom, soft, modular, capacitive touch. <br>
Week 3 (Nov 3 - 8, project review Nov 4): Integrate all electrical components on bread board, lights, motors, cap sense, IR proximity sensor. Iterate V2 of mechanical design if problems arise. <br>
Week 4 (Nov 10 - 15): Fab custom PCB shield for mbed, ideally fish shaped. Dynamic modeling of fish movement. <br>
Week 5 (Nov 17 - 22, project mini updates): All hardware done - (f)ish.  Software simulation of FSM in statechart. <br>
Week 6 (Thanksgiving Nov 22 - 24, milestone report due 25th): Software simulation and debug<br>
Week 7 (Dec 1 - 6): Model and implement fish walking <br>
Week 8 (Dec 8-13): Complete and practice project presentation, begin working on writeup. <br>
<br>
Constraints:  We have seven weeks to complete this project, with additional constraints for other commitments we have in our schedule. Additionally, we have a $200 budget constraint, however our materials should not be nearly that expensive.<br>
Risk and Feasibility: The core features of our project should be deliverable on time. All proposed projects parts are available in the CITRIS Invention lab, and we will exclusively use rapid prototyping tools (laser cutting, 3D printing) for all mechanical components to prevent suspension of schedule. One feature that might be difficult is to make the fish “walk” by flopping, because it requires additional modelling, parts, and knowledge on how the fish will interact with the environment. We are also building much of our own hardware, including the fish’s spine, an mbed shield, and possibly our capacitive sensors, which could create unforeseen problems.<br>
<br>
Work Breakdown Structure
<img src="work breakdown structure.png" alt="WBS">
