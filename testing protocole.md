# Preambule

My objective is to be able to understand the elastic properties that my new "alternative-for-elastane design" will bring to the fabric.
Where do we stand in comparision to the tensile properties of traditionnal woven fabrics, between the properties of the "plain woven fabric",as the control sample, an the properties of elastane.

Find how the design can influence the elasticiy of the material
1. the choice of the "plain fabric"
2. the lawout of the slots
  - the length of the slot
  - the distance between slots (lateral)
  - the pace between slots (longitudinal)
  - the orientation of the slots
  - the oveverall density of slots 
  - same logic at the level of the unitary patern...
  
3. the addition of 3d printed shapes onto the fabric 
4. the supperposition of different layers


To do so i need to develop a protocole to measure the elasticity - to plot the stress-strain curves of my sample.
I will be following the principle  of this [uniaxial tensile tester] (https://pubs.acs.org/doi/10.1021/acs.jchemed.6b00639).

Vref:https://zerotohero.engineering/setting-vref-for-drv8825-and-a4988-motor-drivers/



1. strain measurement
- a ruler laying flat along the fabric, in tension
-linear actuator https://www.youtube.com/watch?v=Fn6uOHqrGCs

powering the linar actuator with an arduino board and a stepper motor:
https://www.makerguides.com/drv8825-stepper-motor-driver-arduino-tutorial/

2. stress measurement 
- using weights
- using a newtonmeter
- using a tension gauge (load cell)

# C'est parti

my first "mock-up": 


main issues: first, the innacuracy in the elongation measurement: the movement is not in the plane, the clip holding the fabric is tilting and rotating around itself, lifting the cursor in the air. Then the range and the pacing of weight i can apply is limited to the the combination of weights i have. 11 of small one, 4  big ones. I would like to apply a more accurate force and in a wider spectrum. Ideally reaching 5 N.


iterarion 1


iteration 2
