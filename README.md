# Camera-Calibration
About the single,mutiply and stereo camera system calibration and implement with opencv in python.
### 1.Pinhole Camera Model
### Summary  
Camera calibration total include 16 parameters:  
Only camera related: 10 instric parameters:  
Camera to pixel: f,dx,dy,Xc,Yc; Distortion: radial(k1,k2,k3), tangential(p1,p2).  
Camera Pose in world coordination:  
Rotation: Rx,Ry,Rz;  
Translation: Tx,Ty,Tz;

### 2.Calibration Implement
![image](https://user-images.githubusercontent.com/42021698/143153407-c7072c71-a4fc-43fc-8640-87d420311230.png)

### 3.Perspective Transform
![image](https://user-images.githubusercontent.com/42021698/143153541-b154e04f-8bc8-46e6-98e1-170eceec3c95.png)

