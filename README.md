# Publishing an Mobile App

>This is Not a Step by Step guide, rather a helpful set of tips that will save you time through the process of publishing an app.



## PlayStore Android
Now that you have your App ready for distribution follow these steps to publish the app to Apple/Play store:

Before start make sure you have:
- Signed APK 
- Google [Developer Account], (if you don't have one ask in your team for help)
- A set of Assets (banner image, icon, at least 2 screenshots of the application)
- Group of testers with goggle's account (for alpha/beta release)
- Create the Application in Google Play Console

---

### Assets

---


#### Screenshot
Take 2 screenshots of the app while running on Emulator, then upload those to screenshot panel in the form step.

#### High-res icon
- 32-bit PNG (with alpha)
- Dimensions: 512px by 512px
- Maximum file size: 1024KB

#### Feature graphic (Banner image)
- JPEG or 24-bit PNG (no alpha)
- Dimensions: 1024px by 500px

### Testers
---

log in **Google Play Console** go to **Settings > Manage testers >** then create list of testers and add their emails to the list

---

### Publishing
---

##### Store listing

- Complete the form with all the required fields, you will need to include the required images here.

##### Content Rating
- Complete the Content Rating Review
 
##### Others
- **Manage Production Releases:** you can create Alpha, Beta or Production Releases, select your release and upload a valid signed APK
- Set a group of countries where the app will be available.

#### TIP
>if you miss anything in the process of publishing the app, you will find an alert icon in the left menu pointing to root of the issue.

#### Resources
- [Become a Publisher]
- [manually upload apk]

______

## IOS APPLE STORE


Before start make sure which distribution process you want to run: 
- [AD HOC]  
- [Test Flight]


Now that you know which process to Run, continue with the steps for exporting the project with `xcode`

**Important Note**

>Make sure you have the right **Provisioning Profile** when signing the app in your `xcode` (Ask your team for credentials)


Now that you have exported your app via `xcode` you can upload it to **iTunes Connect** via [Application Loader]


Once you have uploaded your `.ipa` with [Application Loader]  follow next steps

### Step 1: Configure Certificates, Identifiers & Profiles `*`

---


- Go to https://developer.apple.com/
- Log in as White Prompt Member (_Ask your team for credentials_)
-  Select **Certificates, Identifiers & Profiles**
-   **Select > Provisioning Profiles** _from left Menu panel_
-  _from Right Menu Panel_ **Create new Provisioning Profile**
-  Select what type of distribution you need and continue the wizard steps

##### Manage User Devices (AD HOC)
-  **Select > Devices**  _from left Menu panel_
-  **Register User's Device** (_These are the users that will be testing the app_)




### Step 2: Create an IOs App in the Apple Store for AD HOC or public distribution

---

- Go to [iTunes Connect]
- Administration account is support@whiteprompt.com. The password in the the password repository
- Ask the Administrator to [[Create a Development account on Itunes Connect]] 
- Receive and accept the invitation
- Log into https://itunesconnect.apple.com/login
- Go to Apps
- Click the `+` Symbol `->` New App
- Complete the form
 
_If you don't have these accounts ask in your team for support._

##### Required Assets
- 4 screenshot 	of the App
1242 x 2208 pixels for portrait
2208 x 1242 pixels for landscape
http://help.apple.com/itunes-connect/developer/#/devd274dd925

_After completing the form you can send your app for revision_

>use the iTunesConnect dashboard to manage and configure your distribution.


### Step 3:  Distribute an IOs App to testers using TestFlight

---

Test Flight is the preferred method. An alternative would be [[Distribute an IOs App to testers using AdHoc Distribution]]

- Get the email names and email addresses of the testers
- Open https://itunesconnect.apple.com/login
- If you don’t have an account ask the Administrator to [[Create a Development account on Itunes Connect]] 
- Open My Apps
- Go to Test Flight
- Create new Group
- Add testers (_all the testers will need to download test flight app for testing_)

##### Manage Compilations
 You can manage your compilations from 
 **iTunesConnect  > TestFlight > Compilations**
 
 - Add a group of testers to the compilation
 - Remove current compilation (_only if you need_)
 
>The process of publishing your app to apple store will take a couple days depending on what revions you had from the Apple Revision Team



 

















[Developer Account]: https://play.google.com
[Become a Publisher]: https://developer.xamarin.com/guides/android/deployment,_testing,_and_metrics/publishing_an_application/part_3_-_publishing_an_application_on_google_play/

[manually upload apk]:https://developer.xamarin.com/guides/android/deployment,_testing,_and_metrics/publishing_an_application/part_3_-_publishing_an_application_on_google_play/manually-uploading-the-apk/

[Apple Developer Account]: https://developer.apple.com/
[iTunes Connect]: https://itunesconnect.apple.com
[Application Loader]: http://help.apple.com/itc/apploader/
[AD HOC]: https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/TestingYouriOSApp/TestingYouriOSApp.html
[Test Flight]: https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/DistributingYourAppUsingTestFlight/DistributingYourAppUsingTestFlight.html
