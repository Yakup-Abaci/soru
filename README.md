# soru
I am working on a quadplane tilt-rotor in gazebo. I used the model but there is a problem in flight. The vehicle switches during the mission and starts to fall after the ‘FW Done’ message. I thought it was because of the tilt, but I tried a lot and could not find the error. The error still persists and I have attached the model file and parameter file I used. 

https://github.com/user-attachments/assets/18390a39-42ce-44b5-a75a-ce179ee29bfc


I was checking the correctness of the motors and propellers when I noticed something. the motors were wrong. although I wrote them correctly in the .sdf file and in the ardupilot as I found on the internet, the wrong motors are displayed in the ‘motortest’ command. 

https://github.com/user-attachments/assets/1e97f612-2a92-4c6d-9aa3-88d42e5ef73d


I thought that the error might be due to this and corrected the engines. I rearranged the quadplane tiltrotor as it should be. but this time the vehicle somersaults during takeoff and cannot even take flight. I still can't find out what's wrong here.

![image](https://github.com/user-attachments/assets/0986d3b6-4e31-454a-b2e7-eb6a89d57c60)



https://github.com/user-attachments/assets/f9369492-fbbb-428f-867a-3b9c3d60463b



