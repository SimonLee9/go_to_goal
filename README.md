# go_to_goal

melodic 

mobile robot(diff_wheel) moving test with waypoint

source : 
 https://automaticaddison.com/how-to-move-the-turtlesim-robot-to-goal-locations-ros/

<use> -----------------------------------------------------------------------------------------------------

terminal 1.   
 roslaunch go_to_goal turtlesim_waypoint_follower.launch
  
terminal 2.
 rosrun go_to_goal go_to_goal_position
 
------------------------------------------------------------------------------------------------------------

<use 2> ----------------------------------------------------------------------------------------------------
 
terminal 1.
  roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch

terminal 2.   
  roslaunch go_to_goal turtlesim_waypoint_follower.launch
  
terminal 3.
  rosrun go_to_goal go_to_goal_position
  
  
  
  
  ********************************************************************'
  
  sudo chmod +x testbot_waypoint_follower.launch
  
  ********************************************************************'
