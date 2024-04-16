# Publisher & Subscriber Node
How to create publisher and subscriber node  

```  
mkdir -p ~/catkin_ws/src
cd catkin_ws/src  
git clone https://github.com/hussains72/Realsense-on-ROS-NOETIC.git  
cd Realsense-on-ROS-NOETIC/src/beginner_tutorials  
mkdir -p ~/include/beginner_tutorials  
cd ..  
catkin_make
```  

open another terminal and run roscore  

cd catkin_ws  (already opened terminal)  

rosrun beginner_tutorials talker  

open another terminal  

cd ~/catkin_ws  

source devel/setup.bash  

rosrun beginner_tutoials listener 

