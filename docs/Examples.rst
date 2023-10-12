Examples
========

Here you will find useful packages that have been developed for learning! Feel fre to download and use them as you wish.

basic_robot Package
-------------------

This Package contains a basic simulation and simple examples!
Pre-requisites: sudo apt install xterm

Robot Teleoperation
~~~~~~~~~~~~~~~~~~~

Move basic_robot with your keyboard! Run the simulation:

.. code-block:: console
    
        $ ros2 launch basic_robot basic_robot_launch.py 

You should see Webots window and a terminal window. In the terminal window, press the keys to move the robot:

.. image:: /_static/images/examples/teleop.png


Robot ROS2 PID Controller
~~~~~~~~~~~~~~~~~~~~~~~~~

Example of a PID controller for basic_robot implemented usign ROS2. Run the simulation:

.. code-block:: console
    
        $ ros2 launch basic_robot follow_the_line_launch.py 
 

You should see Webots window and the robot should start following the line inmidiatly:

.. image:: /_static/images/examples/line_follower.png