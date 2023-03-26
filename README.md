
# unity_ui_minute-repeater
 
Demo video: https://youtu.be/GatxVSyM_SA

## Introduction
A virtual minute repeater

#### What is it and how does it work?
A minute repeater is a type of complication in a mechanical wristwatch or pocket watch that chimes the time on demand, typically by pressing a button or sliding a lever. The chimes are generated by a set of hammers and gongs that strike different tones to indicate the hours, quarter hours, and minutes.

eg. 10 : 52 : 30 = 10 hrs + 3 quarter hours + 7 minutes
Therefore, hours strike 10 times, quarter strike 3 times, minutes strike 7 times

#### Functionality
 - Time
	  - DateTime.Now() by default
	  - or set custom DateTime
  
  - Clock Pointer Visual Update Interval
	  - Discrete
		  - Pointer rotation practically move every minute
	  - Continuous
		  - Pointer rotation practically move every second
  - Configuration
	  - PlayerPref to store chime interval duration settings
