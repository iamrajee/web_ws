Tutorial: https://medium.com/husarion-blog/bootstrap-4-ros-creating-a-web-ui-for-your-robot-9a77a8e373f9  
source devel/setup.bash  
roslaunch rosbridge_server rosbridge_websocket.launch  
source devel/setup.bash && rosrun web_video_server web_video_server  
roslaunch usb_cam usb_cam-test.launch  
=> Open  (browse src/test_controller/webpages/index.html)  
cd ~/slam_rosmelodic_ws  
source devel/setup.bash  
roslaunch test_slam slam.launch  
=> Control using joystick  