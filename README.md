# Fittr
Fittr is a fitness application that tracks your activity whether it is walking, running or cycling and for every meter you get coins and experience points. The app acts as a B2C in a way that we connect customers to businesses through the vouchers the businesses provides on our app which can be bought by the coins made on the app.


### Authentication
![Login Page](https://user-images.githubusercontent.com/47994224/162997460-d2be1454-99c2-41ef-9c6b-548bb39a4309.PNG|width=100px)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Register](https://user-images.githubusercontent.com/47994224/162997489-6395f87c-bde0-41e7-8321-8f536a536864.PNG)


### Activity Page
#### The available activities are Walking, Cycling and Biking. The google activity api is used to determine whether the user is actually performing these activities or not by returning a confidence, if the confidence is above 50% then the activity is on going and the gps is used to determine locations over time of the user to count kilometers. if the confidence is below the threshold the activity is paused. When an activity is stopped an Activity report is shown.


![Activity Fragment](https://user-images.githubusercontent.com/47994224/162997569-bfb2d6f6-165a-4d34-95be-d75e35110298.PNG)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Walking Paused](https://user-images.githubusercontent.com/47994224/162997614-ea7d7f5d-a99a-483f-93ee-72b77e6dd06e.PNG)
![Walking Not Paused](https://user-images.githubusercontent.com/47994224/162997639-d57fb863-3756-4d8f-a10c-a1954420901b.PNG)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Activity Report](https://user-images.githubusercontent.com/47994224/162997740-2a6ac910-c4d8-4cfa-899d-5be6fc2b2f0f.PNG)

### Vouchers Page
#### Here is the page where users can use their earned coins from the app to buy vouchers.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![WhatsApp Image 2022-04-12 at 4 55 34 PM (1)](https://user-images.githubusercontent.com/47994224/162996722-cde4c4ed-e0dc-4b76-b364-1e6bfca18bbb.jpeg)

### Leaderboard Page
#### In this page there is a drop down list where the user can choose an activity to see it's respective leaderboard.


![Walk](https://user-images.githubusercontent.com/47994224/162999006-ccb87fbf-9b35-41f8-b873-9cfe8fc4fa76.PNG)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Cycle](https://user-images.githubusercontent.com/47994224/162999012-4b725d16-7214-47e4-9dc4-1223c75310b3.PNG)


