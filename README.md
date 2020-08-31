# one-way communication
- It is one-way communication with ROS.
- publisher : ``talker``
- subscriber : ``listener``

## How to run
It need ROS melodic.
```bash

cd ~/catkin_ws/src
git clone https://github.com/happyOBO/one_way_communication.git

cd ~/catkin_ws
catkin build
```


### run roscore

```bash
roscore
```

### run publisher node
```bash
rosrun one_way_communication talker
```

### run subscriber node
```bashs
rosrun one_way_communication listener
```

![Run_gif](./one_way_communication.gif){: width="100" height="100"}
