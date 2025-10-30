MuJoCo, but 4D

### Don't read this section, it's just for me.

```
mkdir build
cd build
cmake ~/Code/mujoco_4d -DCMAKE_BUILD_TYPE=Debug
cmake --build . && ./bin/simulate ../model/humanoid/humanoid.xml 
```