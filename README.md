# Assistive_Vision
Computer Vision based Assistive Technology for blind and visually impaired people
![11](https://user-images.githubusercontent.com/72142324/179363419-e2a1dfba-9dc2-401c-ab3b-f385e9ddd552.png)

# Aim of the Project:
Creation a model which will work to assist visually impaired people. This product will detect objects or any other activities and will reflect the same in the form of audio, so that person can easily know about what’s happening in his/her surroundings.

# Motivation behind the work of project:
In a recent survey it is estimated that 285 million people worldwide are visually impaired, among them 246 million have low vision and 39 million are blind. 9 million children are estimated as visually impaired and among them 1.4 million are irreversibly blind. The fact about visual impairment is surprising on one hand, because despite of enormous medical efforts have been made to wipe out the visual impairment, the number is still breath taking. On the other hand, these facts encourage us to develop object recognition-based assistance for visually impaired people.

# Objectives:
◼️ To detect objects and person 
◼️ To maintain or improve an individual’s functioning and independence 
◼️ To improve visual tracking 
◼️ To identify the characteristics of visual impairments

# Now, lets start with working-
Let's see the architecture first- The overall system comprises of front-end. The back-end framework comprises of three modules: Camera module, Detection module and Audio module as appeared in Fig.
![12](https://user-images.githubusercontent.com/72142324/179363505-a7d4e7e9-9922-42f3-94c8-a6b97e900ca4.jpg)

Final architecture of our proposed product is to recognize object which is there in front of a person i.e. in front of camera which is shown in the following table-

![13](https://user-images.githubusercontent.com/72142324/179363532-0ce0b16b-8891-4310-9674-b10b813067b6.png)



Steps for implementation-

# Step 1: Capturing Object
In the initial phase, we used to webcam to get the image or object. Python provides various libraries for image and video processing. One of them is OpenCV. OpenCV is a vast library that helps in providing various functions for image and video operations. With OpenCV, we can capture a video from the camera.
![14](https://user-images.githubusercontent.com/72142324/179363551-7fcf9d49-dfca-499e-8b20-d2c50df09de9.jpg)

# Step 2: Reading and shaping images of captured object
It loads the image from PC and gives it height, weights and number of channels for each pixel. When working with OpenCV Python, images are stored in numpy ndarray. To get the image shape or size, use ndarray.shape to get the dimensions of the image. Then, you can use index on the dimensions variable to get width, height and number of channels for each pixel.

# Step 3: Putting text over detected image of object
![15](https://user-images.githubusercontent.com/72142324/179363586-268e3491-94a6-422c-a23f-bdd067b3ccb2.jpg)

# Step 4: Audio output
Here by using python module it converts text into audio form and displays it. For that we have used a module called gTTS, which is text to speech convertor.

# Here is the demonstration of the whole work-


https://user-images.githubusercontent.com/72142324/179363617-d089245f-ed44-4dd6-9768-96ca42261313.mp4

Hope, you have liked it!

# Thank you...!


