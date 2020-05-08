# amcl-with-slam
#to bring up the model ingazebo 
roslaunch sk sk.launch
#for gmapping and slam
roslaunch sk_navigation slam.launch
#for Autonomous navigtion using AMCL
roslaunch sk_navigation amcl.launch
