# STREET SURFACE ANOMALY SENSING SYSTEM #

Data set :https://www.kaggle.com/code/sudhanshu2198/real-time-pothole-detection-using-ssd/input                                              
Learned weights: https://www.kaggle.com/code/sudhanshu2198/real-time-pothole-detection-using-ssd/input?select=model.pth 


## METHODOLOGY ##
The methodology employed in the proposed pothole detection and measurement System, is a two-pronged approach that 
combines visual object detection using a camera and the Single shot multibox detector, (SSD) algorithm, along with depth 
measurement using ultrasonic sensors.

### 1. Visual Pothole Detection using Camera and SSD Algorithm: ###
• Camera Placement: A high-resolution camera is strategically mounted at the front of the vehicle, near the car's 
logo. This positioning ensures optimal coverage and clear imaging of the street surface ahead.

• Image Capture and Processing: As the vehicle moves, the camera captures continuous images and video 
frames of the street surface. These visual data are subsequently processed in real-time using the SSD algorithm.

• Object Detection: The SSD algorithm analyses the captured visual data to detect and identify potholes on the 
road. It excels in instantaneous object recognition within images and video frames, Allowing it to swiftly 
pinpoint potholes within the proximity of the vehicle's tires.

• Alert Generation: Upon detecting a pothole, the system generates instant alerts to alert the driver or system 
user, enabling timely and appropriate responses to ensure road safety.

### 2. Depth Measurement using Ultrasonic Sensors: ###
• Sensor Placement: Two “Ultrasonic Sensors” are set upped near the headlights of the Vehicle. This positioning 
is chosen to accurately measure the depth of the potholes that fall within the vehicle's tire range.

• Depth Measurement Process: The “Ultrasonic Sensors” emit ultrasonic waves directed towards the road 
surface. Upon hitting a pothole, these waves return back to the sensors.

• Time-of-Flight Calculation: By calculating the time taken for the ultrasonic waves to return after hitting the 
pothole, the system determines the Distance of the pothole accurately.

• Depth Data Integration: The measured distance data from the “Ultrasonic sensors” are utilized to compute he 
depth of the pothole.



