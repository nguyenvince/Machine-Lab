Project Overview
---------------
This project is a modern automaton that makes use of various mechanisms whose motions are driven by an Arduino and servo motors. The overarching theme of Machine Lab's final collaborative project is a time-keeping clock that is surrounded by each individual student's automaton that will chime in every hour or so. My part of the clock is me watering a flower, and hopefully, watching the flower blossom over time.<br>
![watering flower automaton]()<br>

Below is the documentation of the project
---------------

[First update: April 5. Second update: May 8]
---------------

Theme: a master time-keeping clock equipped with different contributing mechanisms from everyone, each portraying each person's unique hobby or perspective<br><br>
My mechanism: watering plants  
![rough sketch](https://raw.githubusercontent.com/vtn238/machineLab/master/finalProject/IMG_20200405_175443.jpg)<br>  
Some first estimations (April 5):  
* 2 servos + 1 DC/stepper motor
* 3 different levels of activities:
  * Level 1: watering with only arms moving
  * Level 2: watering with both upper body and arms moving (bowing down)
  * Level 3: flower grows from the ground
* Material:
  * Acrylic cut-outs (cheap and easy to fabricate) for 2D shapes
  * 3D-printed components (if needed)<br>
  
Final estimations before assemblage (May 8):
* An Arduino board
* An LED to be attached to the opening of the water can's spout
* 3 servos:
  * 1 for the Scoth Yoke mechanism for the flower moving up and down. At first, I thought I could use a DC / stepper motor here for a continuous motion; however, both of them cannot "remember" their previous position (and thus the position of the blossoming flower). Therefore, to better control the position of the flower, I opted for the servo motor here, its 180-degree rotation suffices one up-down motion.
  * 1 for rotating the character's upper body up and down
  * 1 for rotating the character's arm up and down
* Automaton's material:
  * Acrylic cut-outs for the main frame of the automaton and the Scoth Yoke's servo support panel
  * The rest is 3D printed using stereolithography poly jet technique ensure a smooth finish and high accuracy for the rotating joints. Water-dissolvable support will also be utilized to support the overhang (for example the cylindrical spout of the water can)<br>
  * Some metal wires for linkages between the 2 servos and parts of the character's body
  * Zip ties to secure the main frame to the overall support structure (TBD)
    
[First update: April 7. Second update: May 8]
---------------
Some other rough estimations:
* Dimension: the entire project will likely occupy a box 300mm x 400mm x 150mm (W x H x D)
* Material:
  * Cam for flower: ~~acrylic cut-out (April 7)~~ 3D printed (May 8)
  * Flower, watering can, person: ~~can either be acrylic cut-outs or~~3D printed (ABS/PLA)
  <br>Inspiration for 3D print: https://www.youtube.com/watch?v=kN3ZbkWD0RI
  <br>3D printed hinges: https://www.youtube.com/watch?v=7JhjhgjchfM
  * Linkages: thin copper/aluminium wires
* Design in Fusion 360: attempt to sketch 2D version first
* Joints:
  * Rotating joints: If acrylics cut-outs: use nuts and bolts, If 3D printed: print out hinges as well
  * Permanent joints (person and ground/servo and supporting panels...): glue or screw  

[Updated April 15]
---------------
- I started creating 3D models off Fusion 360 for 3D printed parts. All sketches were drawn using parameters so that I can effectively and quickly prototype the dimensions of the components. Below is the Scoth Yoke mechanism to drive the up-and-down motion of the flower:<br>
![scotch yoke](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(12).png)<br><br>
![scotch yoke](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(13).png)<br><br>
![scotch yoke](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(14).png)<br><br>
<br><br>
- I also looked in to hinges design that can be used for the rotating joints of the person. One such hinge can be seen below:
![scotch yoke](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(15).png)<br>
*The hinge has two protruding hemispheres that fit in the two holes when being pushed into the other part*<br>

[Updated April 21]
-----------------
I got the hinge printed out using two different methods: normal 3D printing and stereolithography poly jet. The later and its motion are definitely smoother. However, both of them work and offer a proof of concept that I can incorporate such hinge mechanism to the design of the person.
![hinge](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/IMG_20200421_173802.jpg)<br>

[Updated April 25]
-----------------
I started working on the person part, which comprises of different components held together by rotating joints:<br>
![person](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(17).png)<br><br>
- The joint between the torso and the pair of legs:<br>
![person](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(18).png)<br><br>
- The joint between the torso and the arms (this joint is enclosed, it cannot be taken apart like the joint with the legs, which prevents torsion and simplifies the design): 
![person](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(19).png)<br><br>
- The cross-section of the arm axle:
![person](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(20).png)<br><br>
- The legs:
![person](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(21).png)<br><br>
- The torso (with its protruding hemispheres that snap into the legs):
![person](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(22).png)<br><br>
- The arms (with its axle that goes through the hole in the torso):
![person](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(24).png)<br><br>
- The hole that allows the arm axle to go through:
![person](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(23).png)<br><br>

[Updated May 3]
-----------------
As I did not find any water can 3D model that completely hollow (so that I can potentially put an LED right inside the spout and light it up whenever the "water" comes out), I modeled my own watering can in Fusion 360.
![watering can](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(36).png)<br><br>
Below is the entire scene so far:
![scene](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(37).png)<br><br>

[Updated May 8]
-----------------
As the design of the support structure is not yet determined, I put some 8mm holes near the edge of the main frame which can be used for zip tie / screws later on. As for the 3 acrylic panels of the main frame themselves, acrylic glue will be used to ensure a strong and clean bond.<br>
![8mm holes](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(48).png)<br><br>
As I started to think about where to connect the linkages from the servos to the character, I hollowed out a hook on the back of the character so that a thin wire can be hooked here:<br>
![back's hook](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(49).png)<br><br>
The hook on the back of the arm:<br>
![servo placements](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(56).png)<br><br>

[Updated May 9]
-----------------
This is where the servo controlling the character's upper body will be placed. The wire linkage is not show here but it will be connecting the servo's horn and the hook on the back of the character.<br>
![servo placements](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(55).png)<br><br>
This is where the servo controlling the arm will be placed. The wire linkage is not show here but it will be connecting the servo's horn and the hook on the back of the arm.<br>
![servo placements](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(57).png)<br><br>
There is a small opening on the main frame so that the linkage can go through:<br>
![opening for linkage](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(51).png)<br><br>
The 3 servos seen from the back of the automaton. They are positioned in such a way that their back side faced away from the front of the automata, allowing their wires to go straight out of the automaton's back to the Arduino.<br>
![automaton from the back](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(52).png)<br><br>
Talking about the Arduino, it will be placed behind the automaton, allowing the motions to be seen unobstructively as demontrasted in the drawing below:<br>
![arduino placement drawing](https://raw.githubusercontent.com/nguyenvince/machineLab/master/finalProject/Screenshot%20(52)-1.png)<br><br>

