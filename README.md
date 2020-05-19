# Self-Driving Cars Specialization

![Certificate](./LCV9UWM99C95.png)

## Learn Objects

- Understand the detailed architecture and components of a self-driving car software stack.
- Implement methods for static and dynamic object detection, localization and mapping, behavior and maneuver planning, and vehicle control.
- Use realistic vehicle physics, complete sensor suite: camera, LIDAR, GPS/INS, wheel odometry, depth map, semantic segmentation, object bounding boxes.
- Demonstrate skills in CARLA and build programs with Python.

## Content

### [Introduction to Self-Driving Cars](./01_introduction_to_self_driving_cars)

[Course Link](https://www.coursera.org/learn/intro-self-driving-cars)

This course will introduce you to the terminology, design considerations and safety assessment of self-driving cars. By the end of this course, you will be able to: - Understand commonly used hardware used for self-driving cars - Identify the main components of the self-driving software stack - Program vehicle modeling and control - Analyze the safety frameworks and current industry practices for vehicle development For the final project in this course, you will develop control code to navigate a self-driving car around a racetrack in the CARLA simulation environment. You will construct longitudinal and lateral dynamic models for a vehicle and create controllers that regulate speed and path tracking performance using Python. You’ll test the limits of your control design and learn the challenges inherent in driving at the limit of vehicle performance. This is an advanced course, intended for learners with a background in mechanical engineering, computer and electrical engineering, or robotics.

### [State Estimation and Localization for Self-Driving Cars](./02_state_estimation_and_localization)

[Course Link](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars)

This course will introduce you to the different sensors and how we can use them for state estimation and localization in a self-driving car. By the end of this course, you will be able to: - Understand the key methods for parameter and state estimation used for autonomous driving, such as the method of least-squares - Develop a model for typical vehicle localization sensors, including GPS and IMUs - Apply extended and unscented Kalman Filters to a vehicle state estimation problem - Understand LIDAR scan matching and the Iterative Closest Point algorithm - Apply these tools to fuse multiple sensor streams into a single state estimate for a self-driving car For the final project in this course, you will implement the Error-State Extended Kalman Filter (ES-EKF) to localize a vehicle using data from the CARLA simulator.

### [Visual Perception for Self-Driving Cars](./03_visual_perception)

[Course Link](https://www.coursera.org/learn/visual-perception-self-driving-cars)

This course will introduce you to the main perception tasks in autonomous driving, static and dynamic object detection, and will survey common computer vision methods for robotic perception. By the end of this course, you will be able to work with the pinhole camera model, perform intrinsic and extrinsic camera calibration, detect, describe and match image features and design your own convolutional neural networks. You'll apply these methods to visual odometry, object detection and tracking, and semantic segmentation for drivable surface estimation. These techniques represent the main building blocks of the perception system for self-driving cars. For the final project in this course, you will develop algorithms that identify bounding boxes for objects in the scene, and define the boundaries of the drivable surface.

### [Motion Planning for Self-Driving Cars](./04_motion_planning)

[Course Link](https://www.coursera.org/learn/motion-planning-self-driving-cars)

This course will introduce you to the main planning tasks in autonomous driving, including mission planning, behavior planning and local planning. By the end of this course, you will be able to find the shortest path over a graph or road network using Dijkstra's and the A* algorithm, use finite state machines to select safe behaviors to execute, and design optimal, smooth paths and velocity profiles to navigate safely around obstacles while obeying traffic laws. You'll also build occupancy grid maps of static elements in the environment and learn how to use them for efficient collision checking. This course will give you the ability to construct a full self-driving planning solution, to take you from home to work while behaving like a typical driving and keeping the vehicle safe at all times. For the final project in this course, you will implement a hierarchical motion planner to navigate through a sequence of scenarios in the CARLA simulator, including avoiding a vehicle parked in your lane, following a lead vehicle and safely navigating an intersection.
