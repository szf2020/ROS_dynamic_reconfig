## Author
- **Welin**  2018.03.10

## Description
In this project, it provides how to build server and client in ros dynamic reconguration.
In the script folder, the client is written in python.

In the dyn_cfg_gui package, it is the rqt_reconfigure gui implemented by C++.

## TODO
```sh
    $ mkdir -p catkin_ws/src
    $ cd catkin_ws/src
```
git clone the project from the corrent URL

```
    $ cd ..
    $ catkin_make
    $ source devel/setup.bash
```

Firstly, open the server: rosrun ros_dynamic_test dyn_server



Then, open the client:

rosrun ros_dynamic_test dyn_client or rosrun ros_dynamic_test dynamic_client.py

To run the rosrun dyn_cfg_gui dyn_cfg_gui, the effect is shown below.

![ROS_dynamic_reconfig](docs/images/rqt_recfg.png)
