# My journey

I started that project with the installation of Basic Kit on https://rnfirebase.io/docs/v5.x.x/installation/basic-kit

After the git clone just follow the steps, but in the third step you must to go on firebase console (https://console.firebase.google.com/u/0/) to create a new project.

Now you need to insert the Firebase in your App Android, to do that just click in the android icon and follow the steps, in React Native you can stop these steps after downloading the file 'google-services.json'.

Place this file in the android/app/ directory of your project.

Run 'npm install' to install all the node_modules and 'react-native run-android'

After some tests, i started studying the ~POWER OF FIREBASE~, in next lines i ( will write) / writed about these features.

## Realtime Database

Need to be activated on firebase console

This DB work with JSON, so you must to transform yours SQL Database in JavaScript Object Notation, more about this can be learned on https://medium.com/@mungoidario/realtime-databases-part-1-9a8f1ed171b2 and https://medium.com/android-dev-moz/firebasesql-4ee3d26a3d15 
The first link is about the format of data and the second show how the basic CRUD works with "JSON Database"

https://firebase.google.com/docs/database/web/structure-data?hl=pt-br (this link can be util)

## Auth

Each Auth method need's to be activated on firebase console (facebook, email, google...)

For each Auth method, is necessary to install on your project the respective library and sign in the respective developers page, the next link is a tutorial to install the facebook auth library

https://codeburst.io/react-native-app-with-facebook-sdk-login-and-firebase-storage-606744701207 (to be honest, I didn't follow this link, i just read it)

https://developers.facebook.com to get the App Id and Secret Key

