# Lidar Republisher Node

This is a simple ROS2 node that republishes Lidar scan messages with an updated timestamp. It listens to Lidar scan messages on the `/scan_tmp` topic, updates the timestamp of the message, and republishes it to the `/scan` topic.

## Features
- Subscribes to Lidar scan messages on `/scan_tmp`.
- Updates the timestamp of the incoming messages.
- Republishes the modified messages to the `/scan` topic.
