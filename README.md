# Autonomous Stair Climber Robot

Proof of Concept Demo for a full sized Stair Climbing Robot with the ability to manuever on all ground types. 
It is a fully Autonomous bot which uses complex Vision Algorithms to navigate through ground and detects Stairs without the use of side railings to climb the stairs and maintain a steady trajectory and motion.

It's design is based on the Triwheel Mechanism which provides stable and efficient climbing capabilities to the Robot.

## Notable Features:
* Autonomously detects Stairs and Plans Path for climbing up or down the stairs  
* Fast, Robust, Maneuverable in any terrain, reliable and stable while climbing
* Autonomously detects and changes state b/w Climbing Mode and Driving Mode, independently for front and rear wheels.
* Independently looks for the next Staircase on a landing.
* Keeps payload compartment aligned horizontally always. (using linear actuators and gyro)
* Adjusts bot orientation to remain centrally aligned during Stair Climbing without use of side walls

## Additional Functionalities
* Moves effortlessly on an __inclined plane__ in Driving Mode. 
* __Fast and stable__ on Rough and Rocky terrains.
* Carry payload weight upto __25 Kg__ on a Staircase. 
* __Server and an App to track__ the Bot’s location, sensor data, battery status etc remotely.
* Climb up or down even on __Curved or Spiral Staircase__.

## Out of the box functionalities
* Overcomes scenarios in which only two wheels remain in contact with ground __by Toppling the wheel__
* Passive tumbling of the Tri wheel and Suspensions give __extra stability__ in Driving Mode.
* Simple, efficient and effective __Wheel Mechanism__ for Stair climbing.
* Prevents overload using __Separate Batteries__ for Front and Rear wheels 

## List of simulations and CAD models
* Bot climbing up stairs: https://drive.google.com/file/d/1Pbo2gspeZCrHfcP3bAJMy-b7ooZdyv48/view?usp=sharing
* Output after running path planning and perception: https://youtu.be/ctwr45Y9hrs
* Output after training YOLO: http://shorturl.at/pLR01
* Output after running descent algorithm: http://shorturl.at/hFIUW
* CAD model of robot: https://github.com/karan-13-hub/Stair-Climber
* CAD model for tri wheel design: https://github.com/karan-13-hub/Tri-Wheel-Design
