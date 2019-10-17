This is the README file for my lab.

display.launch is the specified launch file for this lab. It gives the option to use either the xacro or urdf files through the "use_xacro" arg, and the option to use the gui to manipulate the wheels using the "use_gui variable"

robot.urdf is the initial robot urdf file and contains the old version of the robot before xacro was used in the lab. This version has no wheels. 
robot.xacro contains the code to create an xacro version of the robot, including all movable wheels.