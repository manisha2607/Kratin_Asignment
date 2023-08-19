# health_management_webapp
  This app basicaly developed for guiding a user of age greater than 65 years.
# Run on locals
  a] Make the clone of this repository.
  b] Open your terminal and go to the appropriate folder.
  c] Run command npm install.
  d] Set-Up your own MongoDb url and required environment variables.
  e] Ater that run command node index.js
# Technology Used
  a] NodeJs
  b]ExpressJs
  c] MongoDb
  d] EJS
  e] Backend npm--- colors, cors, dotenv, ejs, express, express-ejs-layout, mongoose, morgan
# Features-----
   a] First a user visits then he/she will redurect to the home page.
   b] In home page at the top he will see a navbar, in which first he/she see brand name, search bar with search button, Resister and, sign-in buttons apart from this
      He/she can also see a footer with some texts and in body some texts.
  c] If a user click on register button he/she will redirect to register form page here a user can fill details and register in app and after that user will redirect 
     to sign-in page where user can will sign-n by filling email and password.
  d] After sign-in user will redirect to after log in page and can see same navbar with only my-reminder button and go to home button only and in body some texts.
  e] When a user click on my-reminders butoon user will redirct to profile page where user will see important reminders to be healty at the age of more than 65 years.
# Render-URL
  URL--
# Front-Ebd Views
 1] Home Page
 ![home](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/007ad3eb-791b-4d1e-b3ae-56554c0d6b70)

 2] Register-Page
 ![register](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/e0ac66f9-1ef1-4bdf-bfe9-7848065fd515)

 3] Sign-In Page
![login](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/08da5a0e-4be8-4e44-b4dd-8a8bbd6d800f)

 4] After sign-in
![aftersignup](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/b46ca57c-9f5f-4237-bd4e-0fc28617920c)


 5] Profile Page
![profile](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/4f118158-fe58-486b-a2b4-22cf9e4205cd)


# APIs Calling By Postman's Images
 1] For Register HTTP-RWQUEST->POST URL: http://localhost:9595/api/v1/user/register
 ![api resgister](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/e82e0070-2ea7-4565-9962-67cc7dce18a4)

 2] For Log-In HTTP REQUEST->POST URL: http://localhost:9595/api/v1/user/login
![api login](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/d9776b61-e8e0-4820-9288-1ab6ad84f152)

 3] For Adding Activities HTTP REQUEST-PUT URL: http://localhost:9595/api/v1/user/activity
![api activity](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/b269507d-e74a-47fe-b7b7-755bfcf219a5)

 4] For Adding Nutritions HTTP REQUEST-PUT URL: http://localhost:9595/api/v1/user/nutrition
![api  nutritation](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/eb841137-a8b2-4548-a641-81316e464f16)

 5] For Adding Vitals HTTP REQUEST-PUT URL: http://localhost:9595/api/v1/user/vitals
![api vitals](https://github.com/manisha2607/Kratin_Asignment/assets/126694907/abc32913-9b70-403c-b3bf-ad4b21a9f10a)











