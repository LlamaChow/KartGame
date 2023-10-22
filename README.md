# KartGame
This is a fork of the kart game used developed by the Shocker Studios Mart 432 Game Tech and Coding II course. This fork is being used to test my theories regarding the information being sent to the Shocker Studios Driving Sim. In an attempt to simplify the information being sent to the driving sim, I want to change the parameters used from dynamic to kinematic.

When the driving simulator uses dynamic parameters it requires an object's simulated linear acceleration, angular acceleration, and angular velocity. For those without a solid understanding of physics, those who are presesed on time, or simply wish to not with calculus, it can be a bit daunting to work with these types of parameters, this is where the kinematic parameters come in handy.

For the most part, game developers should have some level of familiarity with kinematic parameters, they are often seen as an objects translation, and rotation in most 3D software. However, the difference between the parameters in the 3D software and the parameters used by the driving sim is in what "plane" those parameters are affecting.

The parameters the driving sim requires is not an equivalent exchange that can bve solved by simply passing the values from one to the other. The issue of gimbal lock arises due to the platforms physical limitations. This fork of this project is being used to take as much information from the game it can, and simulating those experiences as best as it can.
