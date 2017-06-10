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
A pltatform moves upon a binary  unknown pattern. 
Assumptions: rigid motion of the platform (translations only) + measurement model of 1.
Goal: How simultaneously recover the pattern and the platform position?
Example: left video is measurements, right one is the posterior probability map to have targets; the rebuilt map

![](https://github.com/victorjourne/master_thesis/blob/master/measurement.gif)
![](https://github.com/victorjourne/master_thesis/blob/master/map.gif)

A new bayesian filter is introduced:
![](https://github.com/victorjourne/master_thesis/blob/master/bayesian_filter.jpg)

3. Targets tracking (Applications)
Three cameras in a cluttered environnent, with occlusion
Ponctual targets, brownian movment. Targets can appear or disappear
Goal: Track targets 

To go deeper, [see my report](Thesis_Victor.pdf)



.