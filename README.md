# Android-mobile-app-of-your-website-with-push-notifications
Create an Android mobile app of your website with push notifications with firebase and OneSignal

Requirements for creating a web application with push notifications 

Step 1. Create A Firebase Project
If you already have an FCM project, skip to Step 2.

![imagen](https://user-images.githubusercontent.com/3398370/113433435-7da6b700-93df-11eb-8439-93af8d93893d.png)

Step 2. Getting Your Firebase Cloud Messaging Token And Sender ID
Click the gear icon in the top left and select Project settings.

![imagen](https://user-images.githubusercontent.com/3398370/113433546-adee5580-93df-11eb-836f-ac58f26633e9.png)

Select the Cloud Messaging tab.
Save the Server key and Sender ID.

![imagen](https://user-images.githubusercontent.com/3398370/113433582-c3637f80-93df-11eb-83a1-05fa87e8778b.png)

Step 3. Login https://onesignal.com/
Configure Your OneSignal App's Android Platform Settings
In the OneSignal dashboard, select your app, then go to:
Settings > Platforms > Google Android

![imagen](https://user-images.githubusercontent.com/3398370/113433632-e2621180-93df-11eb-9adb-731140cbd5c8.png)

Paste your Firebase Server Key and Firebase Sender ID into the fields and click Next all the way to Save.

![imagen](https://user-images.githubusercontent.com/3398370/113433655-ec841000-93df-11eb-8aa4-46f6cecfa0ce.png)


Then Click Native Android then save

![imagen](https://user-images.githubusercontent.com/3398370/113434849-feff4900-93e1-11eb-90e9-c78d8322035a.png)



So copy your App ID

Download to your computer https://github.com/jschaves/Android-mobile-app-of-your-website-with-push-notifications.git 

Paste it in /app/src/main/java/change/name/app/MainApplication.java Line 7

![imagen](https://user-images.githubusercontent.com/3398370/113436036-42f34d80-93e4-11eb-8d15-9ea2914be021.png)

![imagen](https://user-images.githubusercontent.com/3398370/113436579-3fac9180-93e5-11eb-9bf1-a140d94166e5.png)


rename your package, replace change/name with your actual package name, for example if your "package other.name2.app" would have to change the "cahge/name" folders to "another/name2"


