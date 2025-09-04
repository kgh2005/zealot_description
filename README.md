# zealot_description
**tf, joint_state publish** package

## Development Environment

| Component   | Version          |
|-------------|------------------|
| **OS**      | Ubuntu 22.04     |
| **ROS**     | Humble Hawksbill    |

## Build

```bash
colcon build --packages-select zealot_description 
```

## Run

```bash
ros2 launch zealot_description display.launch.py 
or
ros2 launch zealot_description gazebo.launch.py  
```
