# Description
Speed detection of vehicle and its tracking plays an important role for safety of civilian lives, thus preventing many mishaps. This module plays a very significant role in the monitoring of traffic where efficient management and safety of citizens is the main concern.

The proposed method consists of mainly three steps background subtraction, feature extraction and vehicle tracking. The speed is determined using distance travelled by vehicle over number of frames and frame rate. 

                               

Steps performed in Jupyter Notebook
1.	We are using Haarcascade classifier to identify vehicles.
2.	Vehicle Tracking - ( assigning IDs to vehicles 
3.  We have used correlation tracker from dlib library.
4. 	Speed Calculation
5. 	We are calculating the distance moved by the tracked vehicle in a second, in terms of pixels, so we need pixel per meter to calculate the distance travelled in meters.
6. 	With distance travelled per second in meters, we will get the speed of the vehicle.


![image](https://user-images.githubusercontent.com/71623089/210834573-b98d8156-9402-4344-8c5c-d4ed680a7923.png)
![image](https://user-images.githubusercontent.com/71623089/210834615-3120557d-5d39-4bb9-880a-1ac9083349f3.png)
