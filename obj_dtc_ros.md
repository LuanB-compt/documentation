# **VISUALIZE THE OBJECT DETECTION WITH ZED2 ON ROS**

### FIRST (SETUP THE PARAMETERS):
```
roscd zed_wrapper/params
nano zed2.yaml                     #set true the "od_enabled" and save
```

### SECOND (LAUNCH THE zed2 AND rviz):
```
roslaunch zed_wrapper zed2.launch
rosrun rviz rviz                   #add the topic "obj_det"
```