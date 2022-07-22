# Raspberry Pi Image and Facial Recognition
This project consists of a Raspberry Pi attached to a camera. The Raspberry Pi takes a picture with its camera and then analyzes that image using both image recognition and facial recognition. The user also has a an option to add a filter to the image, so any faces in the picture will have that filter applied to them.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Yishai O | Frisch High School | Engineering | Incoming Sophomore |

![Headstone Image](https://raw.githubusercontent.com/BlueStampEng/BSE_Template_Portfolio/de8633f62b5da2234992a0178a6a72fd6df7e7e1/branding/BlueStamp-Logo.svg)
  
# Final Code
![IMG_0431 2 Small](https://user-images.githubusercontent.com/108901307/180511854-880e7715-2de8-45d9-9e58-877584b31ed1.jpeg)


https://github.com/Yishai-O/Face-Filter-Code
  
# Final Milestone
My final milestone was to add filters to the facial recognition, so that whenever the Raspberry Pi detected a face in its picture, it would add a filter to the image, so each face would have either a dog, a cat, or a bunny on it. To do this, I had to change the facial recognition that my Raspberry Pi was using, so the code had to be majorly changed from what I had previously, but in the end, it was worth it, because, after adding the code for the filters, the Raspberry Pi could detect faces with pretty high accracy and add a filter of the users choice to it. Unfortunately, there were some problems with the bunny filter being a little bit off, but after some more time on it, it worked most of the time, and the dog and cat filters worked perfectly.

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1658432236/video_to_markdown/images/youtube--VplI8eUAAnA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/VplI8eUAAnA "Third Milestone")

# Second Milestone
My second milestone was to get the facial recognition to work, along with the image recognition and camera. This was quite difficult, as I originally tried to use dlib for facial recognition, but everytime I tried to install dlib onto the Raspberry Pi, it would crash and time-out, and no matter what I did to try and get it to actually install, nothing would work. Therefore, I had to scrap the idea of using dlib and instead used OpenCV, which was less ideal but still worked well for facial recognition. After taking some code from the internet and modifying it to both work and to work with my camera, the Raspberry Pi was able to recognize a face, or multiple faces, and put a box around all the faces it sees. The Raspberry Pi is also still able to run image recognition as well as the facial recognition.

[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1658432168/video_to_markdown/images/youtube--X5k4yrxdcVY-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/X5k4yrxdcVY  "Second Milestone")
# First Milestone
  

My first milestone was setting up and hooking up the camera to the Raspberry Pi, and getting the camera and image recognition to work and to work together. The first step was downloading Raspian, the typical Raspberry Pi's software, onto the SD card, which I then plugged into the Raspberry Pi. Next, I had to plug the Raspberry Pi into a power source and connect the camera, which were both pretty quick to do. I then had to write the code for the camera to take a picture, as well as the code for image recognition, which I was able to get from github. After that, making the camera's image and image recognition work together only required a few tweaks to the original codes for each of them, and to add a controller code to get the two codes to run together. Once I did that, I was able to take a picture and run image recognition on it.

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1658347526/video_to_markdown/images/youtube--KR309z5tlLU-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/KR309z5tlLU "First Milestone"){:target="_blank" rel="noopener"}
