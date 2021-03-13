# low-level-project
My low-level 3D graphics project for the IUPUI course CSCI 43800.

I utilized three.js for this project. I have created a simple demonstration of two F1 cars, one doing a celebratory burnout, and the other spinning out of control.

For the first (blue) car, I can't seem to figure out a way to stop it from moving (maybe it's just the numbers I used?). I don't think what I did is too unrealistic, so I feel it's fine. I feel like this qualifies as an interesting animation, as while it does constantly spin like the example, I also change the position to make it appear as if the invisible driver of the car is performing a burnout.

For the second (red) car, I initially just made it spin and move at a constant speed across the ground. This is a less complex animation, but it is still more than just the example as I have the car move as if it's uncontrollable (and I have it come back, to make it loop; though I could have reset the position instead). Then, while writing this readme, I was thinking of how alternatively I could use a ball model and rotate it in the Z axis so that it looks like it's rolling, but I realized I could do the same thing with the car! So, I changed it. Now, the car flips on its side repeatedly as if it's crashing. Now that's interesting!

Initially, I wanted to make a car controllable with the keyboard. However, I couldn't seem to make it work. The three.js editor exports the custom JS code in a weird way, so I have no idea how to add anything discussed in 437. I also couldn't figure out how to add the capability without bringing in a library, so I just decided to go with the baked-in animation approach. Interactivity will be something I will want to try to add to this demo as practice at some point.

**Acknowledgements**
Ferrari F1 Race Car by Ben Houston - found on clara.io: https://clara.io/view/dcb0b529-b3a9-421e-a1ad-dabfd6717bbc#
three.js editor
