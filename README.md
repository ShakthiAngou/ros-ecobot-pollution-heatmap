# ROS EcoBot: Pollution Sensing + Heatmap Mapping

## Project overview
This is a learning-first robotics project that simulates pollution sensing and mapping to generate a cleanup heatmap. The focus is on understanding core robotics and ROS2 concepts through a software-only pipeline.

The goal is to implement a minimal and realistic environmental robotics pipeline: **robot motion → pose/odometry → pollution sensing → heatmap mapping → visualization**


**By the end of this project, I should be able to:**
- Build and run a multi-node ROS2 system (nodes, topics, parameters, launch files)
- Publish robot state (odometry) and coordinate frames (TF)
- Simulate an environmental sensor (pollution readings with noise)
- Aggregate readings into a 2D grid heatmap map
- Visualize robot + map (RViz or equivalent visualization)

**References:**
1. [ROS 2 Documentation: Humble](https://docs.ros.org/en/humble/index.html)
