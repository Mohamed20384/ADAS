# ADAS

![image](https://github.com/user-attachments/assets/007b8544-f560-4fc5-a19b-472d9d5ad89c)

Essential safety-critical ADAS applications include:

1 - Pedestrian detection/avoidance
2 - Lane departure warning/correction
3 - Traffic sign recognition
4 - Automatic emergency braking
5 - Blind spot detection

These lifesaving systems are key to the success of ADAS applications. They incorporate the latest interface standards and run multiple vision-based algorithms to support real-time multimedia, vision coprocessing, and sensor fusion subsystems.

The moderinization of ADAS applications is the first steps toward realizing autonomous vehicles.

![image](https://github.com/user-attachments/assets/d4c19c75-27bd-4f41-a66e-cf5726634da1)

Integrating state-of-the-art models SGDepth for depth estimation, YOLO for object detection, DeepLabv3+ for scene segmentation, and PINet for lane detection creates a foundation for an Advanced Driver Assistance System (ADAS). SGDepth calculates depth information, important for understanding the layout of the environment, while YOLO detects objects such as vehicles, pedestrians, and cyclists in real-time. Also, SGDepth provides semantic segmentation, allowing the system to delineate road boundaries, lane markings, Additionally, PINet specializes in lane detection, enabling the ADAS to identify lane boundaries and assist drivers in lane keeping tasks. By integrating these models, the ADAS gains capabilities, enhancing its ability to assist drivers in various scenarios, from collision avoidance to lane keeping and night vision, improving road safety and driving experience.


As is clear in the picture, for main script, the arrangement and way the models work together, where the YOLO is used in object detection, and then we send the bounding box of detected objects to the depth model to evaluate the distance of these objects. It is also used in scene segmentation to determine the road, the side walk, and the PINet model.  It is used to divide the road into lanes, which facilitates the organization and movement of cars.
PINet (key points estimation and point instance segmentation approach for lane detection)

![image](https://github.com/user-attachments/assets/928ec93b-1457-41a7-9280-0e377efa7e97)

important approach for self-driving cars as they provide reliable lane detection. By identifying key points and segmenting lane instances, PINet enables the vehicle to maintain its position within lanes, navigate complex road layouts, and execute safe lane-changing maneuvers.

![image](https://github.com/user-attachments/assets/8cfcf663-d398-4127-b83c-36763f0d50d2)


The final output

![image](https://github.com/user-attachments/assets/81e14981-efd8-44e5-aa4d-048c6ee0c1f5)

Videos 

Out 1

Out 2

Out 3

