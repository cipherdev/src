Guide at link: https://github.com/cipherdev/src/wiki/Run-Example-Code
---
Follow step by step:
1. Git source, compile and create websocket
```
mkdir -p ~/catkin_ws/
cd ~/catkin_ws/
git clone https://github.com/cipherdev/src.git
catkin_make
source devel/setup.bash
roslaunch video_stream video_stream.launch
```
2. Open Simualator
```
team1 - ws://127.0.0.1:9090
```

3. Run code example
```
rosrun lane_detect lane_detect _image_transport:=compressed
```
--
