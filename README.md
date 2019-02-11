# Smart-Park-with-YOLO-V3
Maintaining empty parking spot count using YOLO real-time vehicle detection. Code readily runnable in google colab.
Due to occlusions (coming due to the presence of mirror in the middle of camera and parking lot which slightly reflects nearby people passing through), low resolution of video and positioning of cars at different angles in the parking lot and limitations of yolo, it cannot detect every car in all the frames and hence the count fluctuates. 

![](yolo_limit.gif)

Same is the case with Mask-RCNN. But for a different video with high resolution and less occlusions, the case becomes different.

![](more_resolution.gif)
