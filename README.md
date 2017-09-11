# README

This project creates a Photoshaing application similar to Instagram using the tutorial found here:
https://www.youtube.com/watch?v=MpFO4Zr0EPE

The main functionality of the application is to allow a user to register an account, login/logout once they have their account, add new posts to their wall, and display a wall of posts that have accumulated on the app. One additional simple functionality I implemented on top of those described through the tutorial is I allowed for the wall to be viewed by anyone (whether or not logged in) but only users that are logged in can add pictures to the wall. Below you can find screenshots of the application performing the above functionality. 

To run the application you must have Ruby on Rails and ImageMagick installed on your machine. If that is the case, you can cd into the directory containing the project using your terminal or command line, run the command "rails s" to activate the local rails server, then go to "http://localhost:3000" in a web browser. 


![screen shot 2017-09-10 at 11 34 10 pm](https://user-images.githubusercontent.com/21328223/30261284-bb5296e2-9680-11e7-9e4a-8e1070f3020b.png)

Register 


![screen shot 2017-09-10 at 11 36 10 pm](https://user-images.githubusercontent.com/21328223/30261302-da5b24e6-9680-11e7-8667-17c08c5d8935.png)
Successfully registered


![screen shot 2017-09-10 at 11 36 34 pm](https://user-images.githubusercontent.com/21328223/30261319-e92cf0f8-9680-11e7-9906-e7195246f11d.png)
Logout -- are you sure?


![screen shot 2017-09-10 at 11 36 55 pm](https://user-images.githubusercontent.com/21328223/30261329-f6a0bdfa-9680-11e7-9cf8-ade051fec6ab.png)
Successfully Logout 

![screen shot 2017-09-10 at 11 37 20 pm](https://user-images.githubusercontent.com/21328223/30261340-03585490-9681-11e7-8b73-88d10344b3d6.png)
Login 

![screen shot 2017-09-10 at 11 37 44 pm](https://user-images.githubusercontent.com/21328223/30261351-12ad6656-9681-11e7-998e-f0e96bf680ae.png)
Successfully Login


![screen shot 2017-09-10 at 11 38 06 pm](https://user-images.githubusercontent.com/21328223/30261363-1e7f2a50-9681-11e7-8f5e-5daec19885f5.png)
Add picture 

![screen shot 2017-09-10 at 11 38 42 pm](https://user-images.githubusercontent.com/21328223/30261384-34c2b94e-9681-11e7-98fc-d80c1424166e.png)
Select picture to add


![screen shot 2017-09-10 at 11 39 14 pm](https://user-images.githubusercontent.com/21328223/30261398-487f8a0c-9681-11e7-9aec-a5f506ea4190.png)
Successfully adding a picture 


![screen shot 2017-09-10 at 11 39 42 pm](https://user-images.githubusercontent.com/21328223/30261412-5969d02a-9681-11e7-9346-360d188a3e04.png)

View Wall of many pictures -- Zoomed out from normal view to allow for multiple pictures 


![screen shot 2017-09-10 at 11 40 10 pm](https://user-images.githubusercontent.com/21328223/30261424-686b358c-9681-11e7-83a2-7ebc1b893b33.png)

Can't add pictures if logged out 
