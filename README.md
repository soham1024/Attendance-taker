![](https://miro.medium.com/max/2994/1*Q_6ec5gt2qN07ftfLY1Yvg.png)

# Attendance-taker

Technology used :
-openCV (Opensource Computer Vision)
-Python 3.6
-tkinter GUI interface

Here I am working on Face recognition based Attendance Management System by using OpenCV(Python). One can mark thier attendance by simply facing the camera. 

How it works :

>When we run "train.py" a window is opened and ask for Enter Id and Enter Name. 

>Enter name and id then we have to click "Take Images" button. 

>By clicking "Take Images" camera of running computer is opened and it start taking image sample of person. file name is "StudentDetails.csv".

>It takes 60 images as sample. After completion it notify that iamges saved.

>After taking image sample we have to click "Train Image" button. Now it take few seconds to train for the images that are taken by clicking "Take Image" button and creates a "Trainner.yml" file.

>Now all initial setups are done. By clicking "Track Image" button camera of running machine is opened again. If face is recognised by system then Id and Name of person is shown on Image. Press Q(or q) for quit this window.After quitting it attendance of person will be stored as csv file with name, id, date and time.



