In src/description/urdf/body.xacro at line 184-
replace directory with whatever the directory is in your system

Once done, don't forget to catkin_make in parent directory

In simulation/launch you'll find steer.launch that starts RViz and Gazebo

In control/scripts you'll find two files:
publisher
keyboard driver

Run these in two separate terminals. Use keys i, j, k, l, m
in the terminal where keyboard driver is running to control the bot

Don't forget to source the setup.bash file in every terminal you open!
