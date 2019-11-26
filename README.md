# Auth
[![Medium](https://img.shields.io/badge/Medium-Read-green?logo=Medium)](https://medium.com/@greg.perry/auth-in-flutter-97275b29b550) [![Pub.dev](https://img.shields.io/pub/v/auth.svg?logo=data:image/png;base64,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)](https://pub.dev/packages/auth) [![GitHub stars](https://img.shields.io/github/stars/AndriousSolutions/auth.svg?style=social&amp;logo=github)](https://github.com/AndriousSolutions/auth/stargazers)

This library package works with four plugins: 
- [firebase_auth ](https://pub.dartlang.org/packages/firebase_auth)
- [google_sign_in](https://pub.dartlang.org/packages/google_sign_in)
- [flutter_facebook_login](https://pub.dev/packages/flutter_facebook_login)
- [flutter_twitter](https://pub.dartlang.org/packages/flutter_twitter)

All four are used to log into a Firebase backend. If you're familiar with these plugins, you'll be able to quickly use this class library. 
## Installing
I don't always like the version number always suggested in the '[Installing](https://pub.dev/packages/auth#-installing-tab-)' page.
Instead, always go up to the '**major**' semantic version number when installing my library packages. This means always entering a version number trailing with two zero, '**.0.0**'. This allows you to take in any '**minor**' versions introducing new features as well as any '**patch**' versions that involves bugfixes. Semanitic version numbers are always in this format: **major.minor.patch**. 

1. **patch** - I've made bugfixes
2. **minor** - I've introduced new features
3. **major** - I've essentially made a new app. It's broken backwards-compatibility and has a completely new user experience. You won't get this version until you increment the **major** number in the pubspec.yaml file.

And so, in this case, add this to your package's pubspec.yaml file instead:
```javascript
dependencies:
  auth:^4.0.0
```
For more information on this topic, read the article, [The importance of semantic versioning](https://medium.com/@xabaras/the-importance-of-semantic-versioning-9b78e8e59bba).
## How it Works
Below are a series of screenshots depicting how to initialize and authenticate or 'sign in' an individual into your app's Firebase database using a either an email and password or a Google account. The following will sign in 'silently' (i.e. automatically if the user had already signed in in the past.). Note, settings are passed as parameters in the screenshot below. 
[![09inistate](https://user-images.githubusercontent.com/32497443/62817460-d9327b80-bafc-11e9-9e96-4ce2682d49e5.png)](https://github.com/AndriousSolutions/auth/blob/fab7e97246581fa4b6ad91fa95a9d10124347f2c/example/main.dart#L37)
These examples have the class library called in the State object's **iniState**() function, but, of course, you could instead 'initialize' the class library in the **initState**() function and then 'sign in' elsewhere. Below, the **init**() function is used instead just to initialize the class library. 
[![authinit](https://user-images.githubusercontent.com/32497443/62817491-5f4ec200-bafd-11e9-9197-4df5c3cd6180.png)](https://github.com/AndriousSolutions/auth/blob/fab7e97246581fa4b6ad91fa95a9d10124347f2c/example/main.dart#L31) 
[![auth3](https://user-images.githubusercontent.com/32497443/62818193-c1adbf80-bb09-11e9-966b-65a02f03e8c9.png)](https://github.com/AndriousSolutions/auth/blob/fab7e97246581fa4b6ad91fa95a9d10124347f2c/example/main.dart#L92)
![anyomous](https://user-images.githubusercontent.com/32497443/62819280-7d75eb80-bb18-11e9-89a5-6aaf3d1a4214.png)
![google](https://user-images.githubusercontent.com/32497443/62819365-deea8a00-bb19-11e9-9ce5-98ee6c5f2218.png)
[![properties](https://user-images.githubusercontent.com/32497443/62819111-2f5fe880-bb16-11e9-80d2-181a7f845bb3.png)](https://github.com/AndriousSolutions/auth/blob/fab7e97246581fa4b6ad91fa95a9d10124347f2c/example/main.dart#L151)
# Facebook
Even if you've no intention of allowing users to use Facebook to log in, you will have to modify a few files any way so to use this library package. You can then ignore these files as they just need to be there. If you don't add to these three files, you'll get the following error when trying to use this Auth package:
*"The SDK has not been initialized, make sure to call FacebookSdk.sdkInitialize() first."*
![faceSDKerror](https://user-images.githubusercontent.com/32497443/66129610-dceef580-e5b5-11e9-81ee-f1c4fde18037.png)
## On The Android Side
You must acknowledge to Android that the Facebook SDK is being utilized. Hence, a means to initialize it is required. So, go to the 'Android Manifest file' (*android/app/src/main/AndroidManifest.xml*) and add the following _after_ the first tag, **</activity>** but _before_ the last tag, **</application>**. See below.
![facebookManifest](https://user-images.githubusercontent.com/32497443/66130625-9dc1a400-e5b7-11e9-87e9-46659eb5baa2.png)
You can copy and paste the code here:
```php
<meta-data android:name="com.facebook.sdk.ApplicationId"
    android:value="@string/facebook_app_id"/>

<activity android:name="com.facebook.FacebookActivity"
    android:configChanges=
            "keyboard|keyboardHidden|screenLayout|screenSize|orientation"
    android:label="@string/app_name" />

<activity
    android:name="com.facebook.CustomTabActivity"
    android:exported="true">
    <intent-filter>
        <action android:name="android.intent.action.VIEW" />
        <category android:name="android.intent.category.DEFAULT" />
        <category android:name="android.intent.category.BROWSABLE" />
        <data android:scheme="@string/fb_login_protocol_scheme" />
    </intent-filter>
</activity>
```
Now go to the 'styles' (android/app/src/main/res/values/styles.xml) file and add the following:
```php
    <string name="app_name">Your App Name here.</string>
<!-- Replace "000000000000" with your Facebook App ID here. -->
    <string name="facebook_app_id">000000000000</string>
<!-- Replace "000000000000" with your Facebook App ID here.    -->
    <string name="fb_login_protocol_scheme">fb000000000000</string>
```
With that, you can get on with your app even if you're not going to log in with Facebook. Here's what it would possibly look like in your particular file:
![facebookresfile](https://user-images.githubusercontent.com/32497443/66132145-3e18c800-e5ba-11e9-912e-4ae0b19e6dce.png)
**Note:** Place this file in .gitignore so not to save this Facebook App ID numbers on a public Github repository.
# Setup Facebook Login
You will have to go to your [Facebook Developers](https://developers.facebook.com/apps/) account and create or select the app you'll use. 
[![facebookDevelopers](https://user-images.githubusercontent.com/32497443/66140484-d1a4c580-e5c7-11e9-9800-0a49d73dfbda.png)](https://developers.facebook.com/apps/)
Under Settings, click on the show button to copy down your _App ID_ and _App Secret_ those later (Firebase will need them). 
![AppSecret](https://user-images.githubusercontent.com/32497443/66141106-c8682880-e5c8-11e9-8b9a-dc3f21541d07.png)

Click on the 'Quickstart' link below to set up Facebook on the Android side:
[![quickStart](https://user-images.githubusercontent.com/32497443/66137189-57257700-e5c2-11e9-9c63-0b54a9c89fe4.png)](https://developers.facebook.com/docs/facebook-login/android)
The following steps in particular will get your app working with Facebook:
**1. Select an App or Create a New App**
**4. Edit Your Resources and Manifest**
**5. Associate Your Package Name and Default Class with Your App**
**6. Provide the Development and Release Key Hashes for Your App**

# Tell Firebase
Remember, all this effort is to connect to a backend Firebase database. You some things to do in the [Firebase Projects Console](https://console.firebase.google.com/u/0/?pli=1).
[![FirebaseProjects](https://user-images.githubusercontent.com/32497443/66138426-36f6b780-e5c4-11e9-8542-404ec4fdc091.png)](https://console.firebase.google.com/u/0/?pli=1)
You'll have to go into the _Sign-in method_ tab and enable the Facbook option and any other options you may wish to use to log into this Firebase app:
![signInProviders](https://user-images.githubusercontent.com/32497443/66139701-7f16d980-e5c6-11e9-8dd4-48e7fe81f61a.png)

# Use Twitter
You can use Twitter as well if you want to. You'll just need to create an app on Twitter and then supply the **Consumer API keys** to this library package.
[![TwitterDeveloper](https://user-images.githubusercontent.com/32497443/66142039-63adcd80-e5ca-11e9-90e7-f24157ebea29.png)](https://developer.twitter.com/en/apps)
![keysTokens](https://user-images.githubusercontent.com/32497443/66142518-2990fb80-e5cb-11e9-9f84-7f1e03ae2e2e.png)
##### On Medium
This is a class library is covered again in the Medium article, [Auth in Flutter](https://medium.com/@greg.perry/auth-in-flutter-97275b29b550).
[![AuthArticle](https://user-images.githubusercontent.com/32497443/62817669-18160080-bb00-11e9-9279-304cec3ff95f.png)](https://medium.com/@greg.perry/auth-in-flutter-97275b29b550)
##### Other Dart Packages
[![packages](https://user-images.githubusercontent.com/32497443/64993716-5c818280-d89c-11e9-87b5-f35aee3e22f4.jpg)](https://pub.dev/publishers/andrioussolutions.com/packages)
Other Dart packages from the author can also be found at [Pub.dev](https://pub.dev/publishers/andrioussolutions.com/packages)