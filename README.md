<h1>libraries used:</h1>
<p1><b>Opencv</b></p1> used for image and video processing.<br><br/>
<p2><b>Mediapipe</b></p2>: A framework developed by Google for building perception pipelines, such as hand tracking.<br></br>
<p2><b>Matplotlib</b></p2>: used for plotting and displaying images.<br></br>
<p3>%matplotlib inline ensures that plots are displayed directly in the notebook.</p3>
<hr></hr>
<h1>working</h1>
<p4><i>The code in the notebook is designed for recognizing hand gestures using OpenCV and MediaPipe. It begins by installing necessary libraries such as `opencv-contrib-python` and `mediapipe`, followed by importing key modules, including OpenCV for image processing, MediaPipe for hand tracking, and Matplotlib for visualizing the results. 

The process starts by reading an image using OpenCV, which is expected to contain a hand gesture. The image is then passed into MediaPipe’s hand detection model, which is designed to identify various hand landmarks, such as fingertips and knuckles. MediaPipe processes the image and detects these key points, after which the identified landmarks are drawn onto the image using the framework’s drawing utility. 

Finally, the processed image with the overlaid hand landmarks is displayed using Matplotlib, allowing the user to visually confirm the hand detection. This setup can be used as the foundation for further developing a hand gesture recognition system that could classify or recognize different gestures based on the detected landmarks.</i></p4>
<br></br>
<hr></hr>
