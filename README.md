# lcmm_mujoco
## Usage
1. `pip install mujoco`
2. `python -m mujoco.viewer --mjcf=mjcf_lcmm_robot.xml`
## Converting from Fusion to MuJoCo 
- Using this plugin: https://github.com/bionicdl-sustech/ACDC4Robot
- For `AttributeError: module 'time' has no attribute 'stop'` use 
https://github.com/bionicdl-sustech/ACDC4Robot/issues/1
- Make sure to remove all nested components in CAD
