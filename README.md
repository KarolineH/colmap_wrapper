COLMAP wrapper forked from [Local Light Field Fusion (SIGGRAPH 2019)](https://github.com/Fyusion/LLFF)

#### Install
Install COLMAP as described [here](https://colmap.github.io/install.html) \
Install python requirements from requirements.txt

  
#### Recover camera poses

This script calls COLMAP to run structure from motion to get 6-DoF camera poses and near/far depth bounds for the scene.
```
python imgs2poses.py <your_scenedir>
```