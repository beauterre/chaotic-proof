PLAY AROUND: https://beauterre.github.io/chaotic-proof/

# linear chaos?
Exploring fractal complexity from JUST iterated linear equation sets and random selection of these sets.
A surprisingly big fraction (estimated 0.9) of strange attractors in the described, purely linear system seem 
to have fractal properties. Experimentation has shown this occurs in a 2D field of 3 sets of 2 linear equations that take the form
```
x'=ax+b, where
-1.1 > a > 1.1 AND -2.1 > b > 2.1
```
In higher complexities (more sets) and higher dimensionalities (larger sets, like x,y,z) and weighted sets (to be described) fractal properties are less evident, but I highly suspect they will be found.

## Interactive version (code in docs)
https://hjalmarsnoep.github.io/chaotic-proof/

## examples of sets of 6 linear equations (3x2) for two dimensional fractals
![snapshot1](https://hjalmarsnoep.github.io/chaotic-proof/snapshot-images/snap001.png)
![snapshot14](https://hjalmarsnoep.github.io/chaotic-proof/snapshot-images/snap014.png)
![snapshot15](https://hjalmarsnoep.github.io/chaotic-proof/snapshot-images/snap015.png)
![snapshot16](https://hjalmarsnoep.github.io/chaotic-proof/snapshot-images/snap016.png)
![snapshot17](https://hjalmarsnoep.github.io/chaotic-proof/snapshot-images/snap017.png)


## why?
I have had this in my head since I was 20, never made a clear version of it. I used it to create 'magic particle' effects for animations back in 1992 on an amiga, happy that javascript now, 30 years onwards, is WAY more powerful now, then that whole setup ever was even using C..
And I was watching Genius.. Einstein took 11 years creating the theory of general relativity after setting up special relativity and then they got to Picasso and that lead me to the notion of aesthetic realism, which is concerned with the general outlook on reality one has. Well, this is mine.. So, one thing lead to another..
Don't know if an actual proof has been done already (probably)..

I don't really have a plan with this, beyond proving it to my own satisfaction and getting a feel for chaotic systems, 
by exploring this most simple and versatile one.
In other words: A platform for just playing around. Maybe you might even call this... art?
I might coin a few NFT's from it, if I can translate it to solidity. Seems to be very close to javascript.

## Possible next steps:
- Check pre existing literature for mention of flares, electric sheep and thousand/million point sculptures based purely on lineair equations.
- prove that it's not artifacts from the random-generator we are seeing here. 
  > This could be easily proven by switching the random algorithm. I tried variants, but no formal page for that yet.
- I feel these are CLEARLY and self evidently fractals. Actual proof might be trying to zoom in and finding the same structures.
- Snapshot editor 
   >(zoom in/out, change colors and params, higher dimensions and pointcount)
- Creating an animation from snapshots, timed constantly
- Right now each equation has the same "probability", I might just add a weight and see what that does.
  > This would also allow me to animate between different dimensionalities.
  > I might ALSO give a gateway probability, meaning how likely are you to move from one equation to another? This will do something, no idea what yet.
  > The idea is based on this principle being the basis of many, many processes in nature, and I cannot imagine all opposing forces will be equally interconnected.
  > So I will probably get more matches and be more versatile in the kind of graphs produced, if I make these connections variable and one way. 
  > It would allow for multiple interconnected "overlays" to be composited with these gateways. Which is interesting for the next point :)
- evolving the parameters to match as closely as possible any given image
  > for it to be used as a possibly ridonculous image compression tool.
- Timing to audio, by having frequency bands / midi instruments map to parameters.
  > for a nice VJ tool.
- 3D pointcloud visualisation and Blender Export, just for fun and bragging rights on youtube..
- Possible application describing/matching/predicting clusters in deep neural maps?
- Calculating the fractal dimension and searching for a parameter correlation. 
   > a bit hard-boiled to my taste, seems like work.. but if anybody wants to, I'd be interested in the results.. I feel there is a connection, where more balanced opposing forces (shrink/grow, translate left/right) lead to a lower fractal dimension.

