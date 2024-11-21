# ros2-for-beginners-level-2

To test the roboticarm use:
```bash
ros2 topic pub -1 /set_joint_trajectory trajectory_msgs/msg/JointTrajectory '{header: {frame_id: base_footprint}, joint_names: [arm_base_forearm_joint, forearm_hand_joint], points: [ {positions: {0.3, 0.5}} ]}'
```