<img src="http://pngimg.com/uploads/android_logo/android_logo_PNG35.png" alt="drawing" width="50" height="70"/> 

# Android-Testing-Instructions

# Android OS Versions
|Code Name             |Version Number    |Release Date       |Api Level
|----------------------|------------------|-------------------|---------
|Honeycomb	       |3.0 - 3.2.6       |February 22, 2011  |11 – 13
|Ice Cream Sandwich    |4.0 - 4.0.4       |October 18, 2011   |14 – 15	
|Jelly Bean            |4.1.0 - 4.3.1     |July 9, 2012	      |16 – 18	
|KitKat                |4.4.0 - 4.4.4     |October 31, 2013   |19 – 20	
|Lollipop              |5.0 - 5.1.1       |November 12, 2014  |21 – 22	
|Marshmallow           |6.0 - 6.0.1       |October 5, 2015    |23
|Nogat                 |7.0 - 7.1.2       |August 22, 2016    |24 - 25
|Oreo                  |8.0 - 8.1.0       |August 21, 2017    |26 – 27	
|Pie                   |9.0               |August 6, 2018     |28
|Q                     |10.0              |September 3, 2019  |29

# Functional
- Make sure app is using only the required permissions
- Make sure app features works well especially for apis under 21 (below android 5)
	> Some features arn't available for android versions < 21 and need handling, for example status bar color, rounded corners ...etc
- Make sure that the updated versions of the app isn't affected by previous versions database
- validate whether the application provides an available user guide for those who are not familiar to the app
- Validate whether the application performs according to the requirement in all versions of Mobile that is 2g, 3g and 4g
- Validate that the navigation between relevant modules in the application are as per the requirement
- Validate that the page scrolling scenarios are being enabled in the application as necessary
- Validate that the mobile can receive calls and SMS during running the app 
- Ensure that the keyboard input can be minimized in an appropriate manner.
- Ensure that the application provides a method for going back or undoing an action, on touching the wrong item, within an acceptable duration.
- Validate the application prompts the user whenever the user starts downloading a large amount of data which may be not conducive for the application performance.
- Validation of the process where the connection is suspended, the system needs to re-establish for recovering the data directly affected by the suspended connection
# Design
- Make sure all screen designs matches the provided design by UI Designer including places of views,spacings,fonts, colors, icons ..etc 
- Make sure that design fits with all supported devices with different screen sizes
	> validate that the user Interface of the application is as per the screen size of the device, no text/control is partially invisible or inaccessible.
- Make sure that design isn't pixelated in high resolutions screens 
- Make sure that design looks the same for different android versions  
- If the app support tablet make sure the design matches thre requirements
- Make sure app launch icon looks good with different OS versions  
- Make sure that notch doesn't affect app by any way
- Ensure that the buttons should have the required size and be suitable to big fingers.
- Ensure that the icons are natural and consistent with the application.
- Ensure that the validation for the tapping zoom-in and zoom-out facilities should be enabled
- Ensure that the text is kept simple and clear to be visible to the users
- Ensure that the font size is big enough to be readable and not too big or too small.
# Performance
- Make sure app performance isn't affected when loading large lists or doing heavy work in the background
- Make sure that the battery consumption, memory leaks, resources like GPS, Camera performance is well within required guidelines
- Validate application performance when network is changed to WIFI from 2G/3G or vice versa
- Validate whether the response time of the application is as per as the requirements.
# Notifications
- Make sure that notification icon looks fine in all different devices 
- Make sure that fcm notifications is received for android 8 and higher  
# Configuration Changes
- Make sure that the app works as supposed in portrait and landscape modes 
- Make sure app works as supposed (online and/or offline) when turning on network or mobile data connection 
- Make sure that keyboard doens't hide any data entry field  
- Ensure that all strings are converted into appropriate languages whenever a language translation facility is available
# Mobile Settings
- Make sure app works well when changing device language to RTL/LTR languages  
- Make sure app works well with night mode  
- Make sure app works well with different system font sizes 
# Common sense
- Make sure that appropriate loaders appear when needed 
- Make sure appropriate error messages appear in different situations 
- Make sure appropriate dialogs appear in different situations  
# Security
- Validate that the application is able to withstand any brute force attack which is an automated
- Validate whether an application is not permitting an attacker to access sensitive content or functionality without proper authentication.
- Validate that the application has a strong password protection system and it does not permit an attacker to obtain, change or recover another user’s password.
- Validate that the application does not suffer from insufficient session expiration.
- Validate that the application code cannot be regenerated by social engineering tools
- Validate that All the input fields have an appropriate validation technique
- Investigate file caching and prevent any malicious possibilities from the same.
- Prevent from insecure data storage in the keyboard cache of the applications.



 
