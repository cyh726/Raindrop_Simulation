# Raindrop_Simulation
## Flocking Algorithm
* **Cohesion**
Cohesion is a behavior that causes agents to steer towards the "center of mass" - that is, the average position of the agents within a certain radius.
![](https://i.imgur.com/T9uDnVP.png =200x200)
* **Alignment**
Alignment is a behavior that causes a particular agent to line up with agents close by.
![](https://i.imgur.com/U4rrA8R.png =200x200)
* **Separation/Avoidance**
Separation is the behavior that causes an agent to steer away from all of its neighbors.
![](https://i.imgur.com/zDgrcS2.png =200x200)
* **The application of raindrop simulation requires two steps of the Flocking algorithm: `Cohesion` and `Alignment`; however, raindrop simulation does not require a `Separation` step. Because raindrops can be combined with each other. Therefore, raindrop simulation requires an additional `Combination` step.**
## Raindrop in Unity
Implementation method
* **Step 1: Rasterized**
![](https://i.imgur.com/sBfMhj9.png =200x200)
* **Step 2: Draw the main raindrops Deform**
![](https://i.imgur.com/HEgVM1Z.png =200x200)    
* **Step 3: Deform the raindrops**
![](https://i.imgur.com/flnFaA3.png =200x200)
* **Step 4: Move the lattice**
![](https://i.imgur.com/hA1q6qh.png =200x200)
* **Step 5: Draw the trail**
![](https://i.imgur.com/K4EiP3T.png =200x200)
* **Step 6: Deform the trail**
![](https://i.imgur.com/FjPD1Ad.png =200x200)
* **Step 7: Combine raindrops and trails**
![](https://i.imgur.com/poijCU5.png =200x200)