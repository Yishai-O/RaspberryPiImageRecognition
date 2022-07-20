# Raspberry Pi Image and Facial Recognition
This will serve as a brief description of your project. Limit this to three sentences because it can become overly long at that point. This copy should draw the user in and make she/him want to read more.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Yishai O | Frisch | Engineering | Incoming Sophomore |

![Headstone Image](https://raw.githubusercontent.com/BlueStampEng/BSE_Template_Portfolio/de8633f62b5da2234992a0178a6a72fd6df7e7e1/branding/BlueStamp-Logo.svg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was to get the facial recognition to work, along with the image recognition and camera. This was quite difficult, as I originally tried to use dlib for facial recognition, but everytime I tried to install dlib onto the Raspberry Pi, it would crash and time-out, and no matter what I did to try and get it to actually install, nothing would work. Therefore, I had to scrap the idea of using dlib and instead used OpenCV, which was less ideal but still worked well for facial recognition. After taking some code from the internet and modifying it to both work and to work with my camera, the Raspberry Pi was able to recognize a face, or multiple faces, and put a box around all the faces it sees. The Raspberry Pi is also still able to run image recognition as well as the facial recognition.

[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone
  

My first milestone was setting up and hooking up the camera to the Raspberry Pi, and getting the camera and image recognition to work and to work together. The first step was downloading Raspian, the typical Raspberry Pi's software, onto the SD card, which I then plugged into the Raspberry Pi. Next, I had to plug the Raspberry Pi into a power source and connect the camera, which were both pretty quick to do. I then had to write the code for the camera to take a picture, as well as the code for image recognition, which I was able to get from github. After that, making the camera's image and image recognition work together only required a few tweaks to the original codes for each of them, and to add a controller code to get the two codes to run together. Once I did that, I was able to take a picture and run image recognition on it.

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}
