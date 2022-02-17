Controls: 
I figured out tweakpane! You can modify a couple parameters in the menu in the top right

scanDist: distance that agents will scan ahead, in pixels.

scanAngleDivisor: the number to divide Pi by when determining the angle at which agents will scan. Higher numbers thus make narrower 
angles.

decay: Constant that we multiply values by to get decay and diffusion. Lower numbers thus make MORE decay. When this is 1 or greater,
the colors will get MORE intense instead of decaying.

speed: the speed at which agents move, in pixels.

doTime: whether or not the agents' scan angles will change sinusoidally with time.

timeMod: the amplitude of the sine wave used to change the angles over time.