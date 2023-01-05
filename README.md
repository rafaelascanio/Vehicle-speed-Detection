# Description
Speed detection of vehicle and its tracking plays an important role for safety of civilian lives, thus preventing many mishaps. This module plays a very significant role in the monitoring of traffic where efficient management and safety of citizens is the main concern.

The proposed method consists of mainly three steps background subtraction, feature extraction and vehicle tracking. The speed is determined using distance travelled by vehicle over number of frames and frame rate. 

![image](https://user-images.githubusercontent.com/71623089/210834394-1289c62a-3508-4b1d-a326-078dcf6e2b6c.png)

Steps performed in Jupyter Notebook
•	We are using Haarcascade classifier to identify vehicles.
•	Vehicle Tracking - ( assigning IDs to vehicles 
•	We have used correlation tracker from dlib library.
•	Speed Calculation
•	We are calculating the distance moved by the tracked vehicle in a second, in terms of pixels, so we need pixel per meter to calculate the distance travelled in meters.
•	With distance travelled per second in meters, we will get the speed of the vehicle.

#Results
![image](https://user-images.githubusercontent.com/71623089/210834573-b98d8156-9402-4344-8c5c-d4ed680a7923.png)
![image](https://user-images.githubusercontent.com/71623089/210834615-3120557d-5d39-4bb9-880a-1ac9083349f3.png)
