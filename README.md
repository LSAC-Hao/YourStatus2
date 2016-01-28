# YourStatus2
Your law school application status mobile app written in Ionic2

## Goal
Develop a sample cross platform native look mobile app that wraps around existing LSAC websites. 

## Development Tools Selected
Ionic v2 is selected for this project. At this time Ionic v2 is still in beta.

## Development Environment Setup (under Windows)
~~~
1) Download and install node.js (https://nodejs.org/en/download/)
2) In command line, execute ==> npm install -g ionic@beta
3) ionic start d:\YourStatus2 --v2
4) cd d:\YourStatus2; delete app and www folders; unzip app and www folders from this repository into d:\YourStatus2.
~~~

## Build
Additional enviroment and packages may required.
~~~
ionic build ios (on Mac computers)
ionic build android (needs to pre-install Android SDK)
ionic build wp8 (on Windows 8.1 above computers)
ionic build balckberry
ionic build amazon-fireos
~~~

## Debug and Test

With Google Chrome browser. You may want to add parameter "--disable-web-security" to start chrome browser in order to bypass CORS error.
~~~
ionic serve
~~~

Test the app with mobile devices. Go to app store of your mobile phone, download and install "Ionic View", and execute following command. Login to your Ionic View and have fun!
~~~
ionic upload
~~~

## Share the app with your coworker
Send an invitation to your coworker to view your development. If your coworker doesn't have an account with Ionic, He/She will need to follow the instruction to create an account.
~~~
ionic shared xxx@lsac.org
~~~



