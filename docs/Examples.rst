Examples
========

Here you will find useful packages that have been developed for learning! Feel fre to download and use them as you wish.

basic_robot Package
-------------------

This Package contains a basic simulation and simple examples!

Robot Teleoperation
~~~~~~~~~~~~~~~~~~~

Move basic_robot with your keyboard! Firs, run the simulation:

.. code-block:: console
    
        $ ros2 launch basic_robot robot_launch.py

In another terminal, run the teleop_twist_keyboard node:

.. code-block:: console

        $ ros2 run teleop_twist_keyboard teleop_twist_keyboard
