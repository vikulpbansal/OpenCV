# OpenCV

###CannyEdgeDetection.cpp would perform canny edge detection during live video streaming using a webcam.
###One has to change the parameter of cvCaptureFromCAM according to the webcam one is using.
##To compile:
command "g++ -I/usr/local/include/opencv -I/usr/local/include/opencv2 -L/usr/local/lib/ -g -o canny  CannyEdgeDetection.cpp -lopencv_core -lopencv_imgproc -lopencv_highgui -lopencv_ml -lopencv_video -lopencv_features2d -lopencv_calib3d -lopencv_objdetect -lopencv_contrib -lopencv_legacy -lopencv_stitching"
##To run:
command "./canny"
