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

### Phase 1: ROS2 fundamentals
- Learn core ROS2 concepts: nodes, topics, messages
- Set up ROS2 Humble development environment
- Run basic publisher/subscriber examples

### Phase 2: Robot state & motion
- Simulate robot motion in a 2D environment
- Publish robot pose and odometry
- Introduce coordinate frames (TF)

### Phase 3: Pollution sensing
- Define a simulated pollution field
- Sample pollution at the robot’s position
- Publish pollution sensor readings with noise

### Phase 4: Heatmap mapping
- Aggregate pollution readings into a 2D grid
- Maintain running averages per cell
- Publish a pollution heatmap map

### Phase 5: Visualization & integration
- Visualize robot state and heatmap
- Add launch files for reproducible runs
- Record demo and document learning outcomes
- 
**References:**
1. [ROS 2 Documentation: Humble](https://docs.ros.org/en/humble/index.html)
