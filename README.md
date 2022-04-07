# SignupLogin_FIREBASE
A barebones login and signup page using Firebase DB.


From the firebase console. (https://console.firebase.google.com/)
  - signup (it is free and they dont ask you to enter a debt card)
  - add a project, name it however you like
  - create a REALTIME database (start in test mode)
  - Head over to the project overview and press the HTML icon to add firebase to your site.
  - After giving your app a nickname your will see some code on the Add Firebase SDK tab. 
  - Copy YOUR firebaseConfig into the provided firebase.js file.

Mine is on line 7 of the firebase.js file and looks like this -

 const firebaseConfig = {
   apiKey: "AIzaSyCugocTZHfgdfgdf66lEMk97NYq79087s",
   authDomain: "webdev-de8.firebaseapp.com",
   projectId: "webdev-de8",
   storageBucket: "webdev-de.appspot.com",
   messagingSenderId: "13753453451375",
   appId: "1:137584891375:web:7cgfghdfgedf72d21a",
   measurementId: "G-MFEJ"
 };

replace my const firebaseConfig = {...} with your const firebaseConfig = {...}.
