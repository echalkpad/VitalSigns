What the app does
=================
(Scroll below and/or click on "View all of README.md" to install this app)
This Android application interprets  signals from a heart rate monitor which transmits in Bluetooth 4.0. If the application interprets the heart rate to be something that requires attention it will SMS (SMS includes the GPS co-ordinates of the phone) and dial out pre-set numbers of people who may be able to attend to the person who may need medical help.

|Heart rate monitor|---BT-->|phone|---> SMS(phone text) and dialling alerts.



What you will need
==================
- A Bluetooth 4.0 enabled Android phone. The Android version must be 4.3 or above. (If you want to check the android version on you phone do this: Go to apps->select settings->About phone>Android Version)
- A heart rate monitor which transmits in Bluetooth 4.0 (I have used the one at www.mioglobal.com)

Installation
=============
To install the app, click the [link](https://github.com/DennisMat/VitalSigns/blob/master/bin/VitalSigns.apk?raw=true) in your smart phone browser. Then go to download section and install the file VitalSigns.apk. The downloads section may be found either in your browser's option or as an icon among other apps of your smartphone apps. You may have to change the security settings on your phone to allow the installation of this file. On some phones the file may be downloaded with a .zip instead of a .apk extension. In that case rename VitalSigns.zip to VitalSigns.apk using another app like the ES File explorer which can be found for free in the google play store.

Know limitations (you may skip this section)
================
- The heart rate monitor that I've used (the mio-alpha) seem accurate while on a wrist, but it still shows figures( i.e heart rate) if quickly moved from the  wrist to an inanimate object (like a roll of paper). It only shows no heart rate if it is clearly kept away from any object. Note that it functions as expected if one were to turn on the heart rate monitoring after placing/wrapping it on an inanimate object.
- If the phone battery runs out of charge then the app will stop monitoring the heart rate (obviously) and hence will not do what it's intended to do. Potential solution: One way out would be to have the phone transmit continuously to a server (perhaps on the web via WiFi,3G/4G etc.) which is on all the time. A lack of signal from the phone can be interpreted as the phone being battery dead or off or not working.
- When the heart rate monitor is being charged it is likely that the heart rate is not being monitored (for various reasons). In order for the app not to send out a false alarm currently it must be stopped and started again when the heart rate monitor is monitoring again. Potential solutions:  There are 2 ways to get around this problem, one way is to have multiple heart rate monitors so that at a given time the person would be wearing at least one heart rate monitor at a time. The app would have to be significantly modified to accommodate such a configuration. The second way is to have a sort of 'snooze' button with a certain duration (say an hour) in the app. During this time the app should ignore the lack of signals from the heart rate monitor. After this duration the app should start interpreting signals from the heart rate monitor i.e work normally. By this time the heart rate monitor would have been fully charged and the heart rate monitor would be transmitting the heart rate data wirelessly again.  


For those who are feeling generous, a bitcoin address can be found [here](http://tinyurl.com/nntl6pd)

TODO
======
Attempt to dial a number - at least 4 times.


