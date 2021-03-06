# VTOL-UAV
Volansi Project Demonstrating Current Skills
* Purpose - Demonstrate the ability to design and rapid prototype concepts for potential employment as a Design Mechanical Engineer with Volansi
* Timeframe - 5/22 thru 5/26 (unsure how complete project will be)
* Materials - What is currently in my office
* Tools - 3D filament printer, 3D resin printer 

## Project - Altering Method for Vertical to Horizontal Flight
Volansi Merck VOLY C10, C20, and M20 utilize fixed horizontal and vertical Rotors
![image](https://user-images.githubusercontent.com/73624921/119247533-28656700-bb3f-11eb-8cd7-1ffc272eb71e.png)

Each design has four points of vertical lift for vertical take-off and landing (VTOL). The use of clockwise and counter-clockwise rotors allows for typical Quad-Copter functionality.

One rotor is used for horizontal movement, in combination with wings allow for fixed-wing (airplane) flight. This is crucial for operating long distances, the use of wings and a single rotor reduces consumption allowing for further distances.

Volansi's design allows for their aircraft to take off in tight spaces and have an easy transition to horizontal flight. In addition, this allows for the aircraft to take-off and land either as a plane or a quadcopter. Multiple safety features, such as having both wing and elevator flaps, create backup systems in case a failure were to occur during operation.

### Vertical to Horizontal Rotor Transitioning
Concept: Utilize two of the vertical rotors to operate in a horizontal position, allowing for the removal of the single horizontal motor and rotor (weight reduction).
*Note - There is a possibility that Volansi has a reason for not having this in their current design, this is unknown. This is intended to be a new design, so no ability to recreate Wingcopter joints and avoid joints used in patent RU180474U1.

Givens:
* Length of the aircraft is 9 feet, from visual proportions the forward structure holding rotors is estimated at 4 inches tall, assuming it's a cylinder. 
* Only designing for the Series 10 aircraft as they have single vertical rotors
* The front rotor concept will be reviewed. The aft is a possibility but would potentially require the addition of another wing (tight on time). 
* Energy usage and weight reduction is assumed to make this project beneficial
* DC Motor that will be used is small, to allow for a prototype 1/3 scale will be used

Concept Design:
![image](https://user-images.githubusercontent.com/73624921/119249481-b21c3100-bb4d-11eb-9d15-9e66aa1be0e7.png)

### Draft Designs
#### The Simple Pivot
Using a 45-degree cut, it???s possible to have a quick swivel to the end of the structure, allowing a quick change from horizontal to vertical. 
![image](https://user-images.githubusercontent.com/73624921/119599586-264b1480-bd9a-11eb-90e1-319ee3fb38c2.png)
![image](https://user-images.githubusercontent.com/73624921/119599612-3a8f1180-bd9a-11eb-9e9b-6ead9b9b725d.png)

A simple 45-degree bevel spur gear was drawn to show a potential application. A final design would require a bearing to allow the joint to rotate smoothly. This gear box would be complicated for the size, and the need for somewhat robust gears would add additional weight to the system that might counteract the benefits. 

![image](https://user-images.githubusercontent.com/73624921/119443439-7b295500-bcde-11eb-8dce-61ad08ced811.png)
![image](https://user-images.githubusercontent.com/73624921/119603819-c9079100-bda2-11eb-93ed-e57cd2b4f112.png)

When transitioning from Vertical to Horizontal flight the rotor does not travel on the vertical plane, resulting in a the rotor facing sideways. This is a loss of energy and a can result in a difficult transition between the two flight profiles.



#### The Not-Simple Pivot
Using a 45-degree cut, and a rotating section it will allow the rotor to travel only on the vertical plane.

![image](https://user-images.githubusercontent.com/73624921/119436889-e4569b80-bcd1-11eb-819d-98846d92e0da.png)
![image](https://user-images.githubusercontent.com/73624921/119436942-f89a9880-bcd1-11eb-8799-28710e5401ef.png)

To keep the rotor on the vertical plane the tube section rotates 90 degrees while the rotor component rotates 180 degree. This requires another gearbox assembly and a bearing to allow for the other degree of rotation.

![image](https://user-images.githubusercontent.com/73624921/119603907-fa805c80-bda2-11eb-811a-b64055653c04.png)
![image](https://user-images.githubusercontent.com/73624921/119604730-6d3e0780-bda4-11eb-8ac7-962f6ae6db9f.png)




#### Elephant Trunk
Using cone like structures multiple joints can be created to allow for streamline horizontal flight and a raised "Trunk" for vertical flight. 
![image](https://user-images.githubusercontent.com/73624921/119436765-af4a4900-bcd1-11eb-8c0a-9c6f884de53c.png)
![image](https://user-images.githubusercontent.com/73624921/119436814-c5580980-bcd1-11eb-9900-28f8881d84fb.png)

Pins with slots allow the cones to fit within each other, and a maximum angle of 20 degrees between joints is possible. It is possible to redesign for each joint to have 22.5 degrees of freedom reducing the length of the assembly by one cone, but this will reduce the diameter of the electrical conduit that could run through the joints. 

The top slot on the cones can be reduced in size which would limit movement, and springs could be used in a relaxed state during vertical flight and compressed during horizontal flight. This could be complicated as the spring constant would need to be tuned to allow for a stiff extension as well as a fluid transition between flight profiles. 

(Due to time and complication of a system this is not modeled with internal components)

## Final Ranking
Each joint was ranked based on weight, ability to transition between vertical to horizontal flight, reliability, mechanical/electrical integration, manufacturability, and maintenance. Ranking is 1 (worst) to 5 (best) with each category having a weighting to emphasize importance. The ranking and weighting is multiplied for each category and all summed for a total rank. Maximum total rank is 5. 

![image](https://user-images.githubusercontent.com/73624921/119607466-42a27d80-bda9-11eb-969d-85aa15ad84a1.png)

When ranking it was found that the Not-Simple Pivot was determined to be the best joint. The Elephant Trunk had too many moving parts and a lot of added weight. The Simple Pivot not travaling on the vertical plane would cause concerning loading and would require the flight computer to compensate RPM during this movement to maintain a fluid transition.


