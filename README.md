accelerometer-and-device-pgb-helloworld
================================

Device works fine but the accelerometer is strange. The API's at phonegap.com   http://docs.phonegap.com/en/3.1.0/cordova_accelerometer_accelerometer.md.html#Accelerometer said something that did not work for me. What worked for me in the config.xml file was

  <gap:plugin name="org.apache.cordova.device-motion" />


So far on a Samsung Galaxy S3 I could not get the accelerometer working, but it was my phone. when I sent the App to someone else it worked fine.


