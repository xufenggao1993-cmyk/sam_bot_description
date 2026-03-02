# sam_bot_description

ros2 launch slam_toolbox online_async_launch.py  use_sim_time:=true

ros2 launch nav2_bringup navigation_launch.py params_file:=/home/xufeng-gao/ros2_ws/install/sam_bot_description/share/sam_bot_description/config/nav2_params.yaml use_sim_time:=true

ros2 launch sam_bot_description display.launch.py