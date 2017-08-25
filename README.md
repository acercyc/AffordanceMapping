# AffordanceMapping

Code for our paper (https://arxiv.org/abs/1708.04391) on mapping body-affordances for dimensionality reduction of spaces of actions.

The best-documented example is the Hexapod code, which has comments discussing architectural
choices of the neural networks and the detailed procedure for training. The reacher code has
many common elements and the detailed explanations are not repeated there.

## Reacher

This code trains a model to control an 8 DoF armature in the presence of obstacles in the
environment. The model sees these obstacles via an overhead depth camera. The model learns
to map the set of reachable points with an approximately uniform control grid.

![Reacher](https://github.com/arayabrain/AffordanceMapping/blob/master/reacher.png "Reacher geometry")

## Hexapod

This code trains a model to control the locomotion of a hexapod robot. The model can direct
the robot to walk or run towards points in the plane.

![Hexapod walking gait](https://github.com/arayabrain/AffordanceMapping/blob/master/hexapod.gif "Hexapod walking gait")
