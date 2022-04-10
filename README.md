# How to use Auth in Firebase for a project

 ### Firebase Auth use Steps:
 * 1. Create a new firebase project in console.firebase.google.com
 * 2. npm install firebase
 * 3. create firebase.init.js and input getAuth to export auth
 * 4. Firebase settings > Authentication > enable Email and password auth
 * 5. Create Login, SignUp component, setup route. 
 * 6. attach from field handle and form submit handle
 * 7. npm install --save react-firebase-hooks
 * 8. useCreateUserWithEmailAndPassword from react-firebase-hooks
 * 9. if user user is created redirect to the expected page.
 * 10. useSignInWithEmailAndPassword for Login
 * 11. Create RequireAuth component ==> check user exists also tract user location.
 * 12. In route wrap protected component by using Require Auth component.

