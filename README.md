import cv2 from pushbullet import Pushbullet from time import sleep #from tkinter import * cam=cv2.VideoCapture(0) img=0 def capture(): print("Capturing image") ret,img = cam.read() print("Image Caputred successfully") k=cv2.waitKey(10000) print("Sending") cv2.imwrite('/home/aiml/Pictures/test.jpg', img) #change image address and put what you have used cam.release() cv2.destroyAllWindows() def send(): #root=tk() #root.geometry("50x70") pb=Pushbullet("_api key from website(generate token) dev=pb.get_device("_deivce name from app_") the image above with open(/home/aiml/Pictures/test.jpg',rb') as pic: #change image address and put what you have used file_data=pb.upload_file(pic,picture.jpg') push=pb.push_file(**file_data) value=push['active'] #if value==true: #messagebox.showinfo("showinfo","message sent") #else: #messagebox.showwarning("warning")

<!---
Honeyyy17/Honeyyy17 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
