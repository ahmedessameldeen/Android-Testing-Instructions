<img src="http://pngimg.com/uploads/android_logo/android_logo_PNG35.png" alt="drawing" width="50" height="70"/> # Android-Testing-Instructions
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

# General
- Make sure app is using only the required permissions
- Make sure app features works well especially for apis under 21 (below android 5)
	> Some features arn't available for android versions < 21 and need handling, for example status bar color, rounded corners ...etc
- Make sure that database tables update doesn't affect any previous version of the app  
# Design
- Make sure all screen designs matches the provided design by UI Designer including places of views,spacings,fonts, colors, icons ..etc 
- Make sure that design fits with all supported devices with different screen sizes  
- Make sure that design isn't pixelated in high resolutions screens 
- Make sure that design looks the same for different android versions  
- If the app support tablet make sure the design matches thre requirements
- Make sure app launch icon looks good with different OS versions  
- Make sure that notch doesn't affect app by any way  
# Performance
- Make sure app performance isn't affected when loading large lists or doing heavy work in the background  
# Notifications
- Make sure that notification icon looks fine in all different devices 
- Make sure that fcm notifications is received for android 8 and higher  
# Configuration Changes
- Make sure that the app works as supposed in portrait and landscape modes 
- Make sure app works as supposed (online and/or offline) when turning on network or mobile data connection 
- Make sure that keyboard doens't hide any data entry field  
# Mobile Settings
- Make sure app works well when changing device language to RTL/LTR languages  
- Make sure app works well with night mode  
- Make sure app works well with different system font sizes 
# Common sense
- Make sure that appropriate loaders appear when needed 
- Make sure appropriate error messages appear in different situations 
- Make sure appropriate dialogs appear in different situations  
 
