# robot_description_Mohamed-AbdElaal

## Project Overview

This package contains a URDF/Xacro description of a two-wheeled mobile robot, built as a ROS 2 package. It includes the robot chassis, two driven wheels, a caster wheel, and LiDAR and camera sensors with custom mesh models.

## Robot Structure

```
base_footprint
└── base_link
    ├── left_wheel_link
    ├── right_wheel_link
    ├── caster_wheel_link
    ├── lidar_link
    └── camera_link
        └── camera_optical_link
```

## Folder Structure

```
robot_description_Mohamed-AbdElaal/
├── urdf/
│   └── robot.urdf.xacro
├── meshes/
│   ├── lidar.STL
│   └── zed.stl
├── package.xml
├── CMakeLists.txt
└── README.md
```

## How to Preview the Robot

1. Open the package folder in VS Code.
2. Install the URDF Visualizer extension.
3. Open `urdf/robot.urdf.xacro`.
4. Run the URDF Visualizer preview command.
5. Click Reload to view the robot model.

## Screenshot
<img width="508" height="222" alt="1" src="https://github.com/user-attachments/assets/0334463d-ac53-48e3-b704-f81af2fe27f1" />
<img width="358" height="297" alt="2" src="https://github.com/user-attachments/assets/36d4a3a1-c564-43c5-b2d4-8edab5a0d675" />

