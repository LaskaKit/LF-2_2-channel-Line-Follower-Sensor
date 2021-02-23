## LF 2.2 channel Line Follower Sensor
### What is it?
LF 2.2 channel Line Follower Sensor is a module with two optical photocells which is generally used for detection of line for the Line Following Robot. 

![LF 2.2 channel Line Follower Sensor](https://github.com/LaskaKit/LF-2_2-channel-Line-Follower-Sensor/blob/main/img/LF-2_2-channel-Line-Follower-Sensor.gif)

### Why?
The Line Following Robots are very interesting for beginners which want to create thier own robot. 
You can join to a lot of competitions where the best Line Following Robot tracks the whole track the fastest. 

Great emphasis of robot is placed on sensors, because poor quality sensor may indicates false detection of line or space and based on these false detections, the Robot may lost a tens of seconds where it is searching the line - let say "the Robot is crazy".
So, the good choice of line following module is very important, hence we introduce our LF 2.2 channel Line Follower Sensor.

LF 2.2 channel Line Follower Sensor includes two photocells, each photocell has own Schmitt circuit which will ensuse correct detection of line and space.

As you can see on video, each output of photocell contains on-board LED what may help with debug.

### How?
The photocell is based from light transmitter and reciever, the trasmitter emites IR light and the detector, phototransistor, detects reflected IR. If IR is not present, it means the sensor in over to line (black tape) otherwise it is outside of line. 
In case the sensor is over to line, the LED is on and the ouput is in the high logic.
