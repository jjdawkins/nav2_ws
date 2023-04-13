# nav2_ws

This repository provides launch files and configuration files to launch the nav2 packages. 

The launch and config files in this repository require environment variables to be set. 

The NAV2_ROOT envioroment variable should provide the full path the the nav2_ws directory. To set in the ~.bashrc file the following command can be used

echo export NAV2_ROOT=/home/ubuntu/nav2_ws >> ~/.bashrc


the ROBOT_NAME enviornment variable should provide the name of the robot being used 

i.e.
echo export ROBOT_NAME=hopper >> ~/.bashrc