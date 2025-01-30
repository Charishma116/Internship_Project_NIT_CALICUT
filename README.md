# 🚀 **Internship Project at NIT Calicut - Agricultural Drone Pathfinding and Obstacle Detection**  
### **National Institute of Technology, Calicut, India**  
**Intern**  
**June 2024 – July 2024**  
**Calicut, India**

---

### 📝 **Project Overview:**  
During my internship at NIT Calicut, I worked on the development of an advanced drone navigation and obstacle detection system tailored for agricultural applications. The main objectives of the project were to:

- **Enable autonomous navigation of drones** through agricultural terrains for various tasks such as mango plucking, pest detection in palm trees, and scaring away monkeys.  
- **Implement advanced pathfinding algorithms** like **RRT*** and **Dijkstra's Algorithm** to navigate obstacles efficiently and ensure safe, collision-free operation.
- **Leverage Lidar sensors** for real-time obstacle detection, ensuring the drones can safely navigate even in dynamic environments with both static and moving obstacles.

---

### 🎯 **Project Objectives:**

1. **Mango Plucking Automation:**  
   - Develop a path planning algorithm to allow drones to navigate to mango trees, identify ripe mangoes using vision systems, and pluck them without damaging the fruit.  
   - Use **RRT*** for fast environment exploration and **Dijkstra’s Algorithm** to calculate the most efficient route to pluck mangoes.

2. **Palm Tree Pest Detection:**  
   - Implement image processing algorithms for the drones to capture high-resolution images of palm trees to detect pests such as the red palm weevil.  
   - Process these images using **MATLAB** to identify early signs of pest infestations and send real-time alerts for pest control.

3. **Monkey Scaring System:**  
   - Develop an autonomous system for drones to patrol farms and scare away monkeys by emitting distress sounds or ultrasonic frequencies.  
   - Use **Dijkstra’s Algorithm** for path optimization to ensure efficient patrol routes without unnecessary overlap.

4. **Obstacle Detection and Avoidance:**  
   - Use **Lidar sensors** for real-time obstacle detection and avoid collisions with both static and moving obstacles such as trees, power lines, and workers in the field.  
   - Implement a dynamic path recalibration system using **RRT*** and **Dijkstra’s Algorithm** to continuously adjust the drone’s route as obstacles are detected.

---

### 🛠 **Technologies and Algorithms Used:**

- **🔧 ROS (Robot Operating System):**  
  For drone control, communication, and integration with sensors, ensuring smooth operation and coordination between drones.  

- **📡 Lidar Sensors:**  
  Used for real-time environmental scanning to detect obstacles (both static and dynamic), enabling safe navigation.  

- **📊 MATLAB:**  
  Employed for **image processing** and analysis of captured data for pest detection, including object recognition and anomaly detection in palm trees.  

- **🧠 Pathfinding Algorithms:**  
  - **RRT*** (Rapidly-exploring Random Trees) for fast exploration of the environment and collision-free path planning.  
  - **Dijkstra’s Algorithm** for calculating the shortest path, ensuring the most efficient route for task completion.

---

### 📹 **Video Demonstration:**

The project features a demonstration video where three drones are shown performing the following tasks autonomously:
- Navigating complex environments with obstacles.
- Detecting and avoiding both static and moving obstacles using Lidar.
- Plucking ripe mangoes, performing pest detection, and scaring away monkeys without collisions.
- Returning to the starting point safely by recalculating paths in real-time.

**Video Link:** [https://drive.google.com/file/d/1eNeNyaK9jrCcd8OTXn3WhCDKSrINB4fq/view?usp=sharing]

---

### ⚙️ **System Workflow:**

1. **Path Planning:**  
   The drone receives destination coordinates and plots a path using **RRT***, considering both static and dynamic obstacles.  
   
2. **Obstacle Detection:**  
   As the drone moves, Lidar sensors detect obstacles in its path. The system adjusts the route in real-time to avoid collisions.

3. **Pest Detection:**  
   The drone captures high-resolution images of palm trees, which are processed using **MATLAB** for pest detection. Alerts are sent to the operator if pests are detected.

4. **Monkey Scaring:**  
   The drone autonomously patrols the farm area, using **Dijkstra’s Algorithm** to find the most efficient patrol route and emits distress signals to scare away monkeys.

5. **Return Navigation:**  
   Upon completing the task, the drone recalculates the optimal return path, avoiding previously encountered obstacles and ensuring a collision-free return.

---

### 🏆 **Achievements:**.
Successfully implemented a multi-purpose drone navigation system capable of performing complex agricultural tasks.
Mango plucking: Developed a system to pluck ripe mangoes without causing damage to the fruit.
Pest detection: Created a reliable method for detecting pests in palm trees using image processing.
Monkey scaring: Deployed an effective method for scaring monkeys from crops using sound deterrents.
Obstacle Avoidance: Ensured the drones could navigate safely and autonomously in real-time environments, avoiding collisions with both static and dynamic obstacles.
🔧 Future Work and Enhancements:
AI Integration: Incorporate AI models for more intelligent and adaptive decision-making in obstacle avoidance and task prioritization.
Data Analytics: Utilize Big Data techniques to analyze patterns in drone performance and improve operational efficiency.
IoT Integration: Incorporate IoT-based monitoring systems for continuous data collection and analysis of drone performance during agricultural tasks.
#📸 Project Media:
Screenshots: ![image](https://github.com/user-attachments/assets/1ecb2da6-c8da-4acc-8065-05a2bc962d64)
![image](https://github.com/user-attachments/assets/7247f9e4-6e87-4595-9ac5-54d56a9b7f35)
![image](https://github.com/user-attachments/assets/2e896590-0acd-4890-9db6-3e1e9dcff6e2)



Video Demo: [https://drive.google.com/file/d/1eNeNyaK9jrCcd8OTXn3WhCDKSrINB4fq/view?usp=sharing]
