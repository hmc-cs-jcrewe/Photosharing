# README

This project creates a Photoshaing application similar to Instagram using the tutorial found here:
https://www.youtube.com/watch?v=MpFO4Zr0EPE

The main functionality of the application is to allow a user to register an account, login/logout once they have their account, add new posts to their wall, and display a wall of posts that have accumulated on the app. One additional simple functionality I implemented on top of those described through the tutorial is I allowed for the wall to be viewed by anyone (whether or not logged in) but only users that are logged in can add pictures to the wall. Below you can find screenshots of the application performing the above functionality. 

To run the application you must have Ruby on Rails and ImageMagick installed on your machine. If that is the case, you can cd into the directory containing the project using your terminal or command line, run the command "rails s" to activate the local rails server, then go to "http://localhost:3000" in a web browser. 


![screen shot 2017-09-10 at 11 19 27 pm](https://user-images.githubusercontent.com/21328223/30260839-881bd646-967e-11e7-8586-87534d75d99e.png)
Register 


![screen shot 2017-09-10 at 11 09 26 pm](https://user-images.githubusercontent.com/21328223/30260596-28dcf42c-967d-11e7-8339-11f910eaa0f0.png)
Successfully registered


![screen shot 2017-09-10 at 11 10 24 pm](https://user-images.githubusercontent.com/21328223/30260606-4398f7ac-967d-11e7-8524-a8ba148a09d4.png)
Logout -- are you sure?


![screen shot 2017-09-10 at 11 10 56 pm](https://user-images.githubusercontent.com/21328223/30260617-53f220b0-967d-11e7-95fe-a73276d1eb85.png)
Successfully Logout 

![screen shot 2017-09-10 at 11 12 10 pm](https://user-images.githubusercontent.com/21328223/30260648-7edf7d04-967d-11e7-9008-04bcf9c10c6f.png)
Login 

![screen shot 2017-09-10 at 11 12 39 pm](https://user-images.githubusercontent.com/21328223/30260659-9399d3f2-967d-11e7-94ca-d54c140d2cad.png)
Successfully Login


![screen shot 2017-09-10 at 11 13 10 pm](https://user-images.githubusercontent.com/21328223/30260700-c97a62f2-967d-11e7-9382-c48ae07b33cf.png)
Add picture 

![screen shot 2017-09-10 at 11 16 15 pm](https://user-images.githubusercontent.com/21328223/30260752-137bbac2-967e-11e7-970d-4ee1eb87dd6e.png)
Select picture to add


![screen shot 2017-09-10 at 11 17 04 pm](https://user-images.githubusercontent.com/21328223/30260774-36bcd3fe-967e-11e7-8a5f-f5d63ddde235.png)
Successfully adding a picture 


![screen shot 2017-09-10 at 11 18 02 pm](https://user-images.githubusercontent.com/21328223/30260802-522d1e6e-967e-11e7-99c4-6a73db570e91.png)
View Wall of many pictures -- Zoomed out from normal view to allow for multiple pictures 


![screen shot 2017-09-10 at 11 18 54 pm](https://user-images.githubusercontent.com/21328223/30260827-70e3fc42-967e-11e7-8b60-4cc3ca7e1c0c.png)
Can't add pictures if logged out 
