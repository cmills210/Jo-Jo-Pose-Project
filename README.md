# Jo-Jo-Pose-Project

The app will work on detecting a pose that we decide to implement, the "josuke higashikata" pose
https://c0.uidownload.com/pngpics/177/1287/josuke-higashikata-jojo-s-bizarre-adventure-character-purple-costume-design-all-star-battle-art-anime-dancer-pose-manga-inspired-art-fictional-hero-illustration.png

Users will be shown a picture that showcases the pose.

The user will then be given a time limit to replicate the pose with their own body.

A warm up count down will begin.
-> The screen shall have a green outline if the pose is matching.
-> The screen shall have a red outline if the pose does not match.

Once the warm up counter has reached 0,a person will be required to hold the pose for 5 seconds.

After the 5 seconds are up, the user will be told if they successfully completed the challenge.

They will then be able to compare their pose (with the pose sketch) compared to the pose's body sketch.

For our project, we will be using Android Studio to develop the app while building off of Google's
MLKit starter app. The project will be taking video in at real time, to ensure standardization of data
the minimum camera resolution will be 1280x720 with a max of 3840x2160(4k) resolution. 

This project will heavily rely on class core areas such as recognition and machine learning with 
secondary focus on tracking. Users will have their body tracked in real time as they attempt to copy the
pose. 

For the purposes of this project, we will be targeting the app to run with low latency on
a Moto Razer Ultra 2025
Hardware Stats:
OS 	Android 15
Chipset 	Qualcomm SM8750-AB Snapdragon 8 Elite (3 nm)
CPU 	Octa-core (2x4.32 GHz Oryon V2 Phoenix L + 6x3.53 GHz Oryon V2 Phoenix M)
GPU 	Adreno 830
Memory 	Card slot 	No
Internal 	512GB 16GB RAM, 1TB 16GB RAM

 	UFS 4.0
For android studio use these settings
Android 16.0 (baklava) and assume 16 gb of RAM.


The primary tasks of this project are
implementing a pose for recognition. Currently the starter app is able to recognize two poses for working out
Adding/improving the data set. We want to detect any notable biases within the project due to physical
features such as skin tone, body proportions and people with non standard amount of limbs. Expanding the 
dataset to eliminate bias for the recognition is critical. 
The final step will be implementing the dataset within the app and ensuring the app works as a functional
game. The app selection should be easy and intuitive for users, so a core part of this project is working
on UI/UX for the app itself.
