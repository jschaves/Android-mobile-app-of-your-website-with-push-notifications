# Android Mobile App of Your Website With Push Notifications
Create an Android mobile app of your website with push notifications with Firebase and OneSignal

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


Step 4. copy your App ID

![imagen](https://user-images.githubusercontent.com/3398370/113517735-242abd80-9582-11eb-8db1-d7b0ef1167e4.png)

Download to your computer https://github.com/jschaves/Android-mobile-app-of-your-website-with-push-notifications.git 

Paste App ID it in /app/src/main/java/change/name/app/MainApplication.java Line 7 and package change.name.app by your package name in line 1

![imagen](https://user-images.githubusercontent.com/3398370/113476805-1db31d80-947e-11eb-9a9d-114a93735904.png)

Step 5. rename your package, replace change/name with your actual package name, for example if your "package other.name2.app" would have to change the "cahge/name" folders to an "other/name2"

![imagen](https://user-images.githubusercontent.com/3398370/113436579-3fac9180-93e5-11eb-9bf1-a140d94166e5.png)

change your id app line 13 /app/build.gradle

![imagen](https://user-images.githubusercontent.com/3398370/113906626-ba562200-97d4-11eb-91cc-cd7145f6b5b9.png)


change the name of your package line 1 and the name of your web in Line 24 /app/src/main/java/change/name/app/MainActivity.java

package change.name.app by your package name
YOUR.HOSTNAME for example google.com 

![imagen](https://user-images.githubusercontent.com/3398370/113437191-7f27ad80-93e6-11eb-8bb9-0c14fd28f7d5.png)

change the name of your package line 1 and the name of your web in Line 16 /app/src/main/java/change/name/app/MyWebViewClient.java

package change.name.app by your package name
YOUR.HOSTNAME for example google.com 

![imagen](https://user-images.githubusercontent.com/3398370/113437541-168d0080-93e7-11eb-82a0-c4e08de7fd8d.png)

rename your package line 3 and line 19 /app/src/main/AndroidManifest.xml
package change.name.app by your package name

![imagen](https://user-images.githubusercontent.com/3398370/113476758-daf14580-947d-11eb-9858-84daded55cd9.png)


Step 6. open the project with Android Studio and compile the APK 

![imagen](https://user-images.githubusercontent.com/3398370/113473152-0bc68000-9468-11eb-8308-d90981046986.png)



