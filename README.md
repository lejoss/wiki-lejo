# Publishing an Mobile App

Now that you have your App ready for distribution follow these steps to publish the app to Apple/Play store:

## PlayStore Android

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

loged in **Google Play Console** go to **Settings > Manage testers >** then create list of testers and add their emails to the list

---

### Publishing (Form Step)
---

- Complete the form with all the required fields, you will need to include the required images here.
- **Manage Production Releases:** you can create Alpha, Beta or Production Releases, select your release and upload a valid signed APK
- Set a group of countries where the app will be available.
- Complete the **Content Rating** Review

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


Now that you know which process to Run, follow the steps for exporting the project with XCODE

**Important Note**

>Make sure you have the right Provisioning Profile when signing the app in your `xcode` (Ask your team for support)


Now that you have exported your app via `xcode` you can upload it to **iTunes Connect** via [Application Loader]


Before continue make sure you have:

- `.IPA` Build File with Provisioning Profile
- [Apple Developer Account]
- [iTunes Connect] Account

if you don't have these accounts ask in your team for support.









[Developer Account]: https://play.google.com
[Become a Publisher]: https://developer.xamarin.com/guides/android/deployment,_testing,_and_metrics/publishing_an_application/part_3_-_publishing_an_application_on_google_play/

[manually upload apk]:https://developer.xamarin.com/guides/android/deployment,_testing,_and_metrics/publishing_an_application/part_3_-_publishing_an_application_on_google_play/manually-uploading-the-apk/

[Apple Developer Account]: https://developer.apple.com/
[iTunes Connect]: https://itunesconnect.apple.com
[Application Loader]: http://help.apple.com/itc/apploader/
[AD HOC]: https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/TestingYouriOSApp/TestingYouriOSApp.html
[Test Flight]: https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/DistributingYourAppUsingTestFlight/DistributingYourAppUsingTestFlight.html
