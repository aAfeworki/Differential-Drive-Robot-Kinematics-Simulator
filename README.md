# Differential-Drive-Robot-Kinematics-Simulator
Forward and Inverse Kinematics simulators for a differential drive robot.  Includes a slider-controlled forward kinematics Simulation and a mouse-click-driven inverse kinematics Simulator,  built using Python and Matplotlib for robotics research and education.



This repository contains forward and Inverse Kinematics simulators for a Differential Drive Robot.  
It provides two interactive simulation modes for educational and research purposes:

- Forward Kinematics Simulator
  Control the robot’s motion using a slider interface and visualize how wheel velocities affect the trajectory.  

![image alt](https://github.com/aAfeworki/Differential-Drive-Robot-Kinematics-Simulator/blob/main/Forward_Kinematics_Simulator_of_Differential_Robot.png?raw=true)

- Inverse Kinematics Simulator
  Set a target position by clicking on the workspace, and the robot computes wheel velocities to reach the desired point.  

![image alt](https://github.com/aAfeworki/Differential-Drive-Robot-Kinematics-Simulator/blob/main/Inverse_Kinematics_Simulator_for_Differential_Robot.png?raw=true)

These tools are designed to support robotics students, researchers, and hobbyists in understanding the fundamental concepts of differential drive kinematics.



✨ Features


      - 📌 Forward Kinematics with interactive sliders  
      - 📌 Inverse Kinematics with mouse-click target input  
      - 📌 Real-time visualization with Matplotlib  
      - 📌 Educational tool for teaching robot motion principles  
      - 📌 Easy to extend and customize  




Requirements:
      Python 3.12


      NumPy


      Matplotlib


      Tkinter (comes pre-installed with most Python distributions)



🚀 Usage


    - Forward Kinematics Simulator
Run:
python forward_kinematics.py

Use sliders to adjust wheel velocities.


Observe robot motion and trajectory updates in real time.


     - Inverse Kinematics Simulator
Run:
python inverse_kinematics.py

Click on the workspace to set a target point.


The robot computes the required wheel velocities and moves toward the goal.




📚 Background

    Differential drive robots are among the simplest and most widely studied mobile robots.
Forward kinematics determines the robot’s trajectory given wheel velocities.


Inverse kinematics computes the required wheel velocities to reach a given target.


This simulator demonstrates both concepts interactively for better understanding.

🤝 Contributing

    Contributions are welcome!
Open issues for bugs or feature requests


Submit pull requests for improvements



📜 License
This project is licensed under the MIT License.

👨‍💻 Author
Developed by Afework Alemu ✨
If you use this in your research or project, or work, please give credit by starring ⭐ this repo!
