# Lidar_Vel
Morgan Hill
Please find 3 .m files:
1) A_RADAR.m
2) B_AWGN.m
3) C_KALMAN_filter.m

1) A is not complete but shows the functions written to replace the phased LIDAR toolbox functions. 
As I do not have this toolbox, I could not verify the outputs except for the peak power.
Also, design the actual antenna is beyond my skill set where I stopped in this project.

2) B also shows the different intermediate functions required to generate the GN.
However, I stopped where I needed the optimization toolbox for fmaximin function.

3) C is compete as running the program will show the KALMAN filter working and the encoder frequency being correctly detected.
The plots basically reproduce the results in the referenced paper.
