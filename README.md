## JetGuard
Introducing JetGuard, the brainchild of Zakaria Jouhari, a smart and agile robot designed to master autonomous navigation and obstacle avoidance. With the power of AI and the Jetson Nano platform, JetGuard effortlessly follows roads and swiftly detects and dodges obstacles in real-time. It's more than just a robot; it's your trusty sidekick for exploring the world of robotics and AI. 

## Combined Jetbot Road Following and Collision Avoidance Tasks

This repository combines the functionalities of Jetbot Road Following and Collision Avoidance tasks. It was created as a requirement for receiving the Nvidia Jetson AI Specialist Certificate.

Jetbot is an open-source AI Robot based on the Nvidia Jetson Nano. It serves educational purposes and can perform multiple tasks including Road Following, Collision Avoidance, and Object Following.
[Jetbot Repository](https://github.com/NVIDIA-AI-IOT/jetbot/tree/master/notebooks).


### Collision Avoidance
Collision Avoidance in Jetbot is a binary classification task consisting of two classes: "blocked" and "free". This functionality ensures Jetbot's safety by helping it avoid collisions with obstacles.

### Road Following
Road Following in Jetbot is a regression task. It teaches Jetbot to detect continuous target x and y coordinates, enabling it to follow a specific path on a track.

### Road Following + Collision Avoidance
This project focuses on combining optimized regression and classification models into one notebook. This integration enables Jetbot to follow a specific path on the track while also being able to avoid collisions with obstacles in real-time by bringing Jetbot to a complete halt.

### How to Run
1. **Road Following Model**:
   - Collect image regression dataset using `data_collection.pynb`.
   - Train and optimize your Road Following model using `train_model.ipynb` and `live_demo_build_trt.ipynb` respectively.

2. **Collision Avoidance Model**:
   - Collect image classification dataset using `data_collection.pynb`.
   - Train and optimize your Collision Avoidance
3. **Combined Script**:
    -Save the TRT models inside the "combine_scripts" folder and run the "RoadFollowing+CollisionAvoidance.ipynb" 
     notebook.

**This is the path we have constructed** :
![WhatsApp Image 2024-05-07 at 23 31 45](https://github.com/Zakariajouhari1/Jetbot-Road-Following-and-Collision-Avoidance/assets/162613293/4d1beba9-9f3c-4322-a803-5dc479c79a25)
 **data collection process** :
![WhatsApp Image 2024-05-07 at 23 45 15 (1)](https://github.com/Zakariajouhari1/Jetbot-Road-Following-and-Collision-Avoidance/assets/162613293/e33c80cb-6955-4295-b850-ca13f2bec035)
** For More info you can check our project paper **
