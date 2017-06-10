# Master Thesis

My project was about **Detection Theory**.
[See my poster](poster.pdf)


## Context

Several cameras scan an unknown map, to find targets. The detection algorithms extract feature points(edges, corners...) and process a **binary representation** of the possible targets location. False alarm probabilities or prior target distribution are unknown.
Three sub problems solved:

1. Probabilities problem
-    Two independent assets with a unknown  probability to say the truth focus on the same environment
-    Goal: How find out the number of targets?
           How far each observer can be trusted?

2. Simultaneous localisation and mapping (SLAM)
A pltatform moves upon a binary  unknown pattern
Goal: How simultaneously recover the pattern and the platform position?

3. Targets tracking
Three cameras in a cluttered environnent, with occlusion
Ponctual targets, brownian movment. Targets can appear or disappear
Goal: Track targets 


![](https://github.com/victorjourne/master_thesis/blob/master/measurement.gif)
![](https://github.com/victorjourne/master_thesis/blob/master/map.gif)


[See my report](Thesis_Victor.pdf)


![](https://github.com/victorjourne/master_thesis/blob/master/bayesian_filter.jpg)

.