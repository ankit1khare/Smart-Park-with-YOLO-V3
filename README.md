# Smart-Park-with-YOLO-V3
Maintaining empty parking spot count using YOLO real-time vehicle detection. Code readily runnable in google colab.
Due to occlusions (coming due to the presence of mirror in the middle of camera and parking lot which slightly reflects nearby people passing through), low resolution of video and positioning of cars at different angles in the parking lot and limitations of yolo, it cannot detect every car in all the frames and hence the count fluctuates. Please don't mind the wrong number of empty spots, I didn't count them before running the program since my focus was to check whether the count fluctuates or not.

![](yolo_limit.gif)

Same is the case with Mask-RCNN. But for a different video with high resolution and less occlusions, the case becomes different. Note that in the video below, the moving car comes in front of the parked on for few seconds and thus YOLO couldn't detect the occluded car and the count changed. Other than that it worked fine for the resolution the video had. 

![](more_resolution.gif)
