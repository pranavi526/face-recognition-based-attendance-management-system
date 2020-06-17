# face-recognition-based-attendance-management-system
This repository contains code for facial recognition using openCV and python with a tkinter gui interface.
Technology used :
-openCV (Opensource Computer Vision)
-Python
-tkinter GUI interface

Here I am working on Face recognition based Attendance Management System by using OpenCV(Python). One can mark thier attendance by simply facing the camera. 
How it works :

When we run attendance.py a window is opened and ask for Enter Id and Enter Name. After enter name and id then we have to click  IMAGE CAPTURE button. By clicking IMAGE CAPTURE camera of running computer is opened and it start taking image sample of person.This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. It takes 60 images as sample and store them in folder TrainingImage.
After taking image sample we have to click Train  button.Now it take few seconds to train machine for the images that are taken by clicking Take Image button and creates a Trainner.yml file and store in TrainingImage folder .
Now all initial setups are done. By clicking ATTENDANCE MARKING button camera of running machine is opened again. If face is recognised by system then Id and Name of person is shown on Image. Press Q(or q) for quit this window.After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time.
