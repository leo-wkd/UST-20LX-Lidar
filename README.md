# UST-20LX-Lidar

If you want to use a UST-20LX lidar
1. git clone urg_c urg_node laser_proc into your_workspace/src
2. catkin_make
3. calibre  src/urg_node/launch/urg_lidar.launch
   There are instuctions on how to calibre in this lauch file

After that
1. launch the above file urg_lidar.launch
2. rosrun rviz rviz
3. change the fixed frame to "laser_scan" (if this option doesn't appear, you can type "laser_scan" yourself)
