# DPDA Simulator
 
Implementation of a standard Turing Machine that simulates a Deterministic 
Pushdown Automata on an input string.
 

The following is an example that checks to see
if a run of ones bounded by #...Q
is in a final set to the right that may look like F111011B
![abc](./GotF/IsStateFinal.jpg)

What main looks like, some of the handoff conventions are inconsistent, idk which is best and most of it is written already:  
![](./celebrity.png)

### WE HAVE LIFT OFF...  
...but could use more testing. Think should focus mostly on unit testing blocks.  

Edge cases:  

* instead of excpeting 0 got E,F,B,G,P or something. In general stuff that could be in / not be in the typical range or boundaries.

* push multiple bundles of different lengths  

* lambdas  

