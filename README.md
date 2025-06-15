# Robotic Crane Simulation

This project simulates a 3D robotic crane arm using MuJoCo in Python.

## Features
- Robotic arm with base rotation, elbow joint, and functional gripper
- Detects and prints real-time cube position
- Picks up and releases a cube using pinch gripper

## Structure
```
├── mujoco_models
│   └── two_robot_scene_with_elbow.xml
├── src
│   └── simulate_robotic_crane.py
└── README.md
```

## Requirements
```bash
pip install mujoco numpy
```

## Run
```bash
python src/simulate_robotic_crane.py
```

---
Simulación diseñada para el **LeRobot Worldwide Hackathon SV 2025**.