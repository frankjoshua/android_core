There was a lot of weird stuff in https://github.com/rosjava/android_core. It was cool but I thought way too complicated. So I created this fork to simplify the project. 
Here is what I did. Combined android_10 and android_15 library projects into a new library project AndroidRosJava. Not as effcient but easier to use. I then moved AndroidRosJava to a new repo at https://github.com/frankjoshua/AndroidRosJava. That way it can be incorporated into new projects with out pulling in all of the sample apps. AndroidRosJava was added using git subtree. The most up to date branch was indigo, so that branch became the new master. Tested it with ROS Kinectic and it works well as a ROS client. There are still some issues runing it as a master (Params don't work). Also, the code was generally updated to work with current versions of Android Studio(tested on 2.1.3). The new minimum api is now 15 instead of 10.

Instructions for using the library can be found at [AndroidRosJava](https://github.com/frankjoshua/AndroidRosJava)

Projects that use this library:<br>
[PocketBot](https://play.google.com/store/apps/details?id=com.tesseractmobile.pocketbot)

rosjava is the first pure Java implementation of ROS.

From [ROS.org](http://www.ros.org/wiki/): ROS is an open-source, meta-operating system for your robot. It provides the services you would expect from an operating system, including hardware abstraction, low-level device control, implementation of commonly-used functionality, message-passing between processes, and package management.

Developed at Google in cooperation with Willow Garage, rosjava enables integration of Android and ROS compatible robots. This project is under active development and currently alpha quality software. Please report bugs and feature requests on the [issues list](https://github.com/rosjava/rosjava/issues?state=open).

To get started, visit the [rosjava_core](http://rosjava.github.com/rosjava_core/) and [android_core](http://rosjava.github.com/android_core/) documentation.

Still have questions? Check out the ros-users [discussion list](https://code.ros.org/mailman/listinfo/ros-users), post questions to [ROS Answers](http://answers.ros.org/questions/) with the tag "rosjava," or join #ROS on irc.oftc.net.

rosjava was announced publicly during the [Cloud Robotics tech talk at Google I/O 2011](http://www.youtube.com/watch?feature=player_embedded&v=FxXBUp-4800).

Looking for a robot platform to experiment with ROS, Android, and cloud robotics? The [Willow Garage](http://www.willowgarage.com/) [TurtleBot](http://www.willowgarage.com/turtlebot) is a great mobile perception platform for [getting started with robotics development](http://www.youtube.com/watch?feature=player_embedded&v=MOEjL8JDvd0).

Visit the rosjava_core wiki for instructions.

http://ros.org/wiki/android_core
