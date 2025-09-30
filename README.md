# CR5-Arm-Robot-IMU-Based-Teleoperation-for-Writing-Drawing

📌 Project Overview

This project was developed on the Dobot CR5 robotic arm.
The focus was to enable the arm robot to imitate human writing and drawing in real time. Using an ESP32 microcontroller and an IMU sensor embedded inside a custom-designed pen, human hand motions were captured and transmitted to the robot over TCP/IP for accurate reproduction within a defined workspace.




![Untitled video - Made with Clipchamp](https://github.com/user-attachments/assets/06d8ba58-7694-4736-90f1-36144d5d489b)

🔧 My Contributions

Sensor Integration: Connected an IMU sensor with an ESP32 for motion tracking.

TCP/IP Communication: Established communication between ESP32 and the Dobot CR5 for real-time teleoperation.

Custom Pen Design: Designed and built a pen housing for the IMU + ESP32, enabling natural handwriting and drawing input.

Arm Teleoperation: Programmed the CR5 to replicate pen motions, writing and drawing in its workspace.

Workspace Limitation: Defined robot workspace boundaries to ensure safe and accurate reproduction.

🛠️ Tools & Technologies

Hardware: Dobot CR5, ESP32, IMU sensor (MPU6050 or similar), custom-designed pen

Communication: TCP/IP protocol

Programming: C++ / Python for ESP32 & robot integration

Methods: Teleoperation, Motion Capture, Real-Time Control

🚀 Features

Real-time teleoperation of a robotic arm via IMU input.

Writing and drawing reproduction within a limited workspace.

Custom pen design with embedded electronics for natural human interaction.

Scalable framework for remote teleoperation applications.

🎥 photos:


![5](https://github.com/user-attachments/assets/5e3dba37-f8f7-4cc7-bab9-f0fed751c803)


![Untitled video - Made with](https://github.com/user-attachments/assets/fed5a6c2-897b-482d-bef0-8edaed7d3c6c)

✅ Outcome

Successfully implemented IMU-based teleoperation for the CR5 robotic arm.

Achieved accurate writing and drawing reproduction in real time.

Demonstrated potential applications in remote operation, teaching, and creative tasks.
