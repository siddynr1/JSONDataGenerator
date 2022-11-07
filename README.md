# JSON Data Generator

For ease I have created all the files and config which needed to be in place for instrumenting the application with NR. You just need to perform minor modifications as follows: 

### Android Studio 

* Install Java 
* Download Android Studio from https://developer.android.com/studio 
* Install Android SDKs
* Once you have the application on your machine, open the application code in Android studio 
  * Run `./gradlew build`

### On New Relic Portal 
* Go to New Relic > Add Mobile Application 
* Select Android 
* Follow the instructions as mentioned
* In step 5 you will get the token, copy that inside onCreate() after setUpUi() 
* Keep following the instructions which are mentioned in NR portal 
* At the end build your application using the play button on the top of android studio next to your simulator. 
* If you want to track what is happening in the background, leverage Build button in the bottom of taskbar (for live updates)
* Once an application is built and launched, generate some load on your application. 
* It will take 5-10 mins for an application to appear in the portal. 
