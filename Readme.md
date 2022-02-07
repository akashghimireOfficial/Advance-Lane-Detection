### **Advance Lane Detection Using Computer Vision** 
*This repo is about findind Lane of road with instruction such as Radius of the road, how far the car is from the centre of the lane and so on.*

## Problems
1. **Camera Distortion**
                  
                  There are two types of Distortion:

- **Radial Distortion**
It happens as because of the divergence cause by camera lens and images don't form as expected. In this case staright lines appears to be curved.

- **Tangential Distortion**
It happenns when images taking lens are not perfectly alligned with the imageing Plane.



## Solving these Problems

# Camera Distortion:
*Camera Distoration Can be solved with computer vision technique called ***Camera Callibration***.*

To solve this problem we use Distortion Cofficient(both tangential and Radial) and in addition to this we will need camera matrix(a 3*3 matrix which consist information regarding focal length and optical center information of the camera.)

For further information related to this look into the jupyter notebook file *Camera Callibration* and to get more detail information related to this topic Fillow this site.
        [Camera_callibration_info](https://docs.opencv.org/4.x/dc/dbb/tutorial_py_calibration.html)