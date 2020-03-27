# command line tool, which can be helpful when ROS is not behaving
the way you expect.
```
roswtf
```
# fatal error: ros/ros.h: No such file or directory 
**make sure that the statement**
```
include_directories(
 include
 ${catkin_INCLUDE_DIRS}
)
```
**is not commented in cmakelists.txt**
