Full Install
============

Includes all of the following:

* Automow Repositories (from auburn-automow)
* Serial Repositories (from wjwwood)
* Additional Hardware Repositories
* ROSOSC Repositories


OSX (/opt):

    rosinstall ~/devel/automow /opt/ros https://raw.github.com/Auburn-Automow/automow_rosinstalls/master/full.rosinstall
    
OSX (/home):

    rosinstall ~/automow ~/ros https://raw.github.com/Auburn-Automow/automow_rosinstalls/master/full.rosinstall 

Ubuntu:

    rosinstall ~/devel/automow /opt/ros/electric https://raw.github.com/Auburn-Automow/automow_rosinstalls/master/full.rosinstall