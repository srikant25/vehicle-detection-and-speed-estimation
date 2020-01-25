# vehicle-detection-and-speed-estimation
here we can detect the car and estimate the velocity of that car\\
Algorithm
step1- load the car video
step2- for vehicle detection pretrained haar casaded classier.
step3- once a car is detected ,using the cascadeclassier() function on the haar
cascade devoloped
step4- vehicle tracking(assigning IDs to vehicle) we use corelation tracker from
dlib library.
step5- now time is started which was initialize to 0
step6- Using the ratio in the image for each cm travelled by the detected image
and real-time distance in meters, the actual distance covered by the car is cal-
culated.
step7- As soon as the car reaches the center of the detection window whose
distance is already known to us the time is stopped.

step8- Now the actual distance calculated is divided by the time calculated
and velocity is obtained.
