# smart-traffic-light-system
#OBJECTIVE
The main objective of the project is to save waiting time for vehicles and fuel consumption. Smart traffic light managing can also help in reducing environmental pollution. Since traffic signals will be changed based on traffic density on the road, it will result in less congestion on roads and hence less number of accidents.

#METHODOLOGY
 Initially Image Acquisition is done. Image of the road is captured with the help of web camera.
 RGB to gray conversion is done on the image and then image correction is done to achieve Image Enhancement. This process is called Image Pre-processing.
 Edge detection of this image is done thereafter with the help of Canny edge detection operator.
 After edge detection procedure, the number of vehicles is counted through Object Recognition and based on this count the density of vehicles on the road is determined by Deep Learning methods.
 If density is found to be greater than a threshold value, the traffic signal turns green, else the process repeats itself. 


