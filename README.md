# KinectGestureBingMap
Using Kinect sensor to detect gesture and operate on Bing Map

1. Zoom In
 - Put your both hands up and close together for a short time to trigger the zoom in operation
 - Once zoom in operation triggered, move your hands apart to perform zoom in 

2. Zoom Out
 - Put your both hands up and apart from each other, keep the pose stable for a short time to trigger the zoom out operation 
 - Once zoom out operation triggered, move your hands together (shorten the distance) to perform zoom out
 
3. Navigation
 - Only put your right hand up, stop at a point and keep the pose for a short time to trigger the navigation operation
 - Once the navigation operation triggered, move your right hand to any direction you want
 
 Requirements:
 
 1. Kinect Sensor
 2. VS 2015
 3. Install Bing Maps WPF control, Put your Bing Map Key in MainWindow.xaml - CredentialsProvider="YOUR BING MAP KEY"
 - https://msdn.microsoft.com/en-us/library/hh745791.aspx
 - https://www.microsoft.com/en-us/download/confirmation.aspx?id=27165
