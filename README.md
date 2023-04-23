# Weapon-detection-using-surveillance-system

In this project, I have used YOLOv3 (You Only Look Once, Version 3) which is a real-time object detection algorithm that identifies specific objects in videos, live feeds, or images. It is a pre trained model, trained on COCO dataset. Here, we train this model again on weapons dataset to increase the accuracy of the model. Then we input a video and using OpenCV we send frames of the object in the video to YOLOv3. It then detects whether there is a weapon in the frame and gives the output of the frame with the weapon. Below are the screenshots of the results obtained on inserting different videos in the program.

![Screenshot 2023-01-10 125706](https://user-images.githubusercontent.com/131551577/233838002-bd4fd92c-bff8-47c8-8c03-87aa871b92e2.png)
Frame of video with weapon in it.


![2](https://user-images.githubusercontent.com/131551577/233838008-d1b2f8bb-f3d6-4dc9-901f-6a6745b97e71.png)
Frame of video without weapon.


![3](https://user-images.githubusercontent.com/131551577/233838019-d46768b1-c71e-4f89-9e98-c44a47df6b42.png)
Frame of video with weapon in it.
