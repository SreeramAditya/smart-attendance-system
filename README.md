# smart-attendance-system

Maintaining attendance is very important in all organizations for checking the performance of an Employee.

We are going to build this project using dlib which uses 128 point face detectors which outputs these 128 points from all the face and compares them with existing faces. This model uses the integrated webcam to capture the video frame. The image of the person captured in the video frame is compared with the encodings of the faces of the pre-trained model. If there is a match, then the image of the employee is recognised and attendance is marked along with timestamp into a log file(excel file).

Project Flow
We can divide the process of developing  smart attendance system into the following steps:

1.Open the integrated webcam when the user clicks mark attendance button.

2. Detecting the face in the video stream.

3. Recognising the face in the video stream.

4. Displaying bounding boxes around the detected face with the name.

5. Mark the attendance along with name and time in a log file(excel file).

To accomplish this, we have to complete all the activities and tasks listed below

Create dataset 

Face detection using dlib 

Import Necessary Libraries

Face Encoding

Video Capture 

Capturing the input frames 

Face Recognition

Convert the image from BGR to RGB

Encoding the input image

Compare input image with known faces

Mark Attendance

Load the data to CSV file

Displaying the result

Application Building

Build an HTML Page

Build the python flask app

Run the application

