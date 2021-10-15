# Yolov4-opencv-python

Implementation of OpenCV for object detection using one stage detector model, yolo-v4. 
Object detection can be done in two ways: by using one stage detector model like Yolo models family or two stage detector model. the difference between these two detection models is the detection speed and accuracy. Two stage model use a preliminary stage to detect region of interest before classification. One stage detector, working without this preliminary step make them suitable for real time object detection.


## Results

### Detection on image
After the detection is done on the image, we display the detected objects labels and their number
![detection_on_image](https://user-images.githubusercontent.com/48753146/137457380-7ea8341f-fc84-4178-8136-ee223dc53a54.jpg)
![Capture](https://user-images.githubusercontent.com/48753146/137461201-9e0cfddd-a852-49e7-9554-c05fc700eac0.JPG)


### Detection on video (To display the result, we coverted the video into gif format)
![video_detection_gif](https://user-images.githubusercontent.com/48753146/137457868-4e9608c9-01f0-4ddb-8e56-dd45e1433018.gif)

# Requirements
Install pandas, opencv and time.

