![Concept artwork of an industrial humanoid robot in a graphite test bay](assets/robotics-banner.jpg)

# Khoa Nguyen

**Electrical engineering · Robotics perception · Autonomy**

I’m an electrical engineering student at UT Dallas working on sensing and calibration for Project NOVA’s autonomous electric vehicle. I’m interested in how robots build a reliable 3D view of their surroundings from multiple sensors.

[Portfolio](https://minhkhoanguyen.com) · [LinkedIn](https://www.linkedin.com/in/minhkhoang/) · [Project NOVA](https://self-driving.utdallas.edu/)

## Targetless LiDAR–camera calibration

I designed a calibration workflow for NOVA’s 1811 vehicle to estimate the position and orientation of four ZED X stereo cameras relative to an Ouster OS1 LiDAR. The prototype uses shared scene geometry to align LiDAR and stereo-depth point clouds without a dedicated calibration target.

- **Registration.** Prototyped the pipeline in Python and Open3D. FPFH describes local geometry, RANSAC estimates an initial alignment, and ICP refines it.
- **Evaluation.** Visualized preliminary alignments and designed tests for repeatability, alignment error, and runtime across different scene geometry, sensor overlap, and lighting.

[Explore the 1811 vehicle repository](https://github.com/Nova-UTD/1811-fall-2026)

## Selected engineering work

- **Vehicle integration.** Streamlined NOVA’s ROS 2 launch workflow, wired radar power and Ethernet, and used Linux networking tools to investigate connectivity on the onboard computer.
- **Competition robotics.** Co-founded a VEX robotics team, helped build two competition robots, and redesigned motor and sensor mounts in Onshape. The team reached the finals at Katy Love of the Bots and qualified for the Texas Region 3 Championship.
- **Embedded prototyping.** Built a C++ and Arduino prototype that reads steering and pedal inputs and converts steering position into PWM signals for a six-LED display.

## Technical tools

**Robotics and perception** · `ROS 2` · `Open3D` · `OpenCV` · `RViz`  
**Software and systems** · `Python` · `C++` · `Linux` · `Docker` · `Git`  
**Hardware and modeling** · `NVIDIA Jetson` · `Arduino` · `Onshape` · `MATLAB`
