# Iready-bot Documentation

## How to use
To use the iready bot you must first open your next lesson in reading then hover your cursor over the spot you want the bot to constently click (should be something with nothing there on the lesson) then you keep the cursor there and start the bot. 

## Good to know
Make sure to ALWAYS start with Reading becuase it will automatically switch to math 

## About
This bot uses image recongnition to detect user UI in the iready website to keep there timer awake to keep your minutes up. It clicks your sceen at a constant rate of 1 mins and after a certain ammount of time it will log out of your assignment and re login to restart there stopwatch that makes sure your doing work. This robot does NOT do your assinment just keeps your time up

## What is a long/short assignment
a long assignment is a normal assignment but has more steps to exit and enter the assignment again selecting the correct one will help the robot know what is going on. To identify what is a long assignemnt check if your exit buttin has a circle around it. if that is a yes you have a short assignment
  
## Troubleshooting License

	The license does not work: Unable to authenticate.
**This means that the autheentication code does not work and you need to contact the software provider for help.**

	The license does not work: Could not find the key.
**This means the the product key you have entered is incorrect please make sure its type EXACTLY with all dashes and symbols**

	The license does not work: The key is blocked and cannot be accessed.
**This means you most likely missed a payment and need to contact the software provider to unblock your license**

	The license does not work:
**For this issue please contact software provider**
  
## Troubleshooting Software
If the software keeps responding with
>	I cannot see it

### **This means that theres an issue with the image recognition to fix screenshot the thing the software is trying to look for and add it to the images file with the corresponding file name as the orginal**

**If this does not work make sure to adjust the confidence level These are what they do**
```py
confidence1 = 0.9 #Exit button 1 this is the x button with a circle around it
confidence3 = 0.8 #next lesson button this is the button in the home page that says "next lesson"
confidence4 = 0.8 #arrow button this is the button after clicking the next lesson button
confidence5 = 0.9 #go button this is the button that says "go" right before starting a long assignment
confidence6 = 0.9 #exit button 3 this is the button that says "are you sure you want to exit"
```
