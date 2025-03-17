# LeKiwi-sim


## Usage

1. `conda activate lekiwi`
2. `cd <lekiwi-sim repo>`
3. `python -m mujoco.viewer --mjcf=scene.xml`

The robot mjcf is [mjcf_lcmm_robot.xml](mjcf_lcmm_robot.xml)

## Install

1. `conda create -n "lekiwi" python=3.10`
2. `conda activate lekiwi`
3. `pip install mujoco==3.3.0`

## Converting from Fusion to MuJoCo 
- Using this plugin: https://github.com/bionicdl-sustech/ACDC4Robot
- For `AttributeError: module 'time' has no attribute 'stop'` use 
https://github.com/bionicdl-sustech/ACDC4Robot/issues/1
- Make sure to remove all nested components in CAD
- Simplify large meshes(like omniwheels) using a [mesh simplifier](https://myminifactory.github.io/Fast-Quadric-Mesh-Simplification/) if mujoco complains about too many faces
