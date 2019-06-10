# real-time-3d-pose-estimation-with-Unity3D-public


### Video demo: https://www.youtube.com/watch?v=JnFtVC0ou6I&t=2s
<img src="version1.0 demo.png"/>



### Webcam demo: https://www.youtube.com/watch?v=WJVNDUkx74s&feature=youtu.be
<img src="webcam_smoothed_real_time.png"/>




## How do I make it: 
### 1. I use the run.py code from this link to generate 3d coordinates of body parts in real-time. Then did some data transformation. https://qiita.com/keel/items/0d64167850566586d22a. To run this code, some configuration should be done: https://github.com/ildoonet/tf-pose-estimation
### 2. Modified above code to be able to send 3d coordinates to Unity3D using "socket" package in python and C#.
### 3. Create an Unity App based on https://github.com/keel-210/OpenPose-Rig. 
### 4. I learn from this code to make character move. https://qiita.com/kenkra/items/7b5634ff7f8c6bf0257a. Note: you have to attach this code to your character.



## Other useful links:
### https://qiita.com/romaroma/items/ffbdae4ecfc4c8ff31cd
### https://github.com/zhenyuczy/openpose_3d-pose-baseline_unity3d
### https://github.com/ArashHosseini/3d-pose-baseline





