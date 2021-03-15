Gem Finder is a [SLAM](https://en.wikipedia.org/wiki/Simultaneous_localization_and_mapping) implemenataion for robot to find gems in an unmapped world. The robot has sensors that are able to detect the gems in a certain distance from the robot. The measurements from these sensors can be used to help the robot to locate itself and navigate through the map to retrieve targeted gems using SLAM. The sensors will provide the bearing and distance to the gem relative to the robot’s location. Both of
these measurements contain noise. The amount of noise will be proportional to the distance away from the robot.

The red dot is where the robot is located with an arrow indicating the heading of the robot; the blue dot is the estimated location given by SLAM. The grey sqaure is where hte gems are located and the black dots are the estiamted location of the gems. Once a gem is collected the letter indicating the type of the gem will disappear. Once all targeted gems are collected the goal is reached and the program will halt.

![SLAM Gem Finder](/slam_gem_finder.gif "SLAM Gem Finder")]
