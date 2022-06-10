# Gym-App
![ezgif com-gif-maker(1)](https://user-images.githubusercontent.com/102428805/173081828-bc90bc5c-a805-4c5f-8d4e-e2c9077a41c7.gif)

## Project Aim and Description
The aim of this project was to create a template app for a chain-gym company, similar to
Energie Cardio, Econogym etc. The idea is to act as a membership-app. A person interested in
working out at Surge Gym locations could sign up at a physical location, however they also
have the option of doing so using our app.
Our app allows a user to sign up, where they provide us with their details and then an account is
created for them. Following this, they can log in and have access to our physical gyms and the
services inside the app.

The app allows a user to view all the locations of Surge Gyms, allows them to view which group
classes are happening on which date, and provides information about personal trainers. They
may also pay their fees using the app, and view selected brand partners. In the future, this could
open up further monetization platforms via referrals.
For this project we used Firebase to handle our database. Registered users can change their
password through email notifications. Additionally, users may sign in using their Google or
Facebook accounts (which are linked to Firebase). A QR code is generated for the user, which
is meant to act as a scannable verification for use at the physical locations (ie instead of a card,
they can scan their QR code from the app and enter).

## Functional and Non-Functional Requirements

### Functional:
These requirements are classified as “must-haves” and need to be included for the app to be
considered a viable product. For the purposes of our app some function requirements would
include:
- User needs to be able to create account and log in, be verified
- Should be able to sign in via Google
- Should be able to sign in via Facebook
- User should be able to reset their password via some ‘forgot password’ method
- The software should provide users with a unique QR code to be scanned at gym
locations for verification
- Should allow users to view class schedules
- Should allow users to sign out
- As part of the gym’s monetization strategy, users should see a section showing brand
partners
- Users must be able to choose which type of gym package they want (premium, basic,
etc)
- System should have a working, scalable database

### Non-Functional:
These requirements are those which refer to quality attributes. While not 100% essential, they
will make the user experience of our app better. Some requirements:
- Should run on a very large number of devices (Tested on the older API 27)
- Should not be ‘laggy’
- Should not be difficult to navigate, use
- User should be able to understand what the app does, what they are doing in it
- App should have a consistent colour scheme/theme
- Should not be prone to crashes

### User Stories
As the user, I should be able to login or register through the landing page.
As the user, I should be able to login through google.
As the user, I should be able to login through facebook.
As the user, I should be able to reset my password before login.
As the user, I should receive an email when resetting my password.
As the user, I should receive a notification when resetting my password.
As the user, I should be able to sign up through the app.
As the user, I should be able to choose my package after putting in my information.
As the user, I should be able to go back and change my information without having to fill in all
the fields.
As the user, I should see my qr code when logged in.
As the user, when scanning my qr code I should see my user identity.
As the user, I should receive a notification after registering.
As the user, I should be able to move to the home page when pressing its appropriate button.
As the user, I should be able to move to the classes page when pressing its appropriate button.
As the user, I should be able to move to the location page when pressing its appropriate button.
As the user, I should be able to move to the trainers page when pressing its appropriate button.
As the user, I should be able to move to the partners page when pressing its appropriate button.
As the user, I should be able to move to the payment page when pressing its appropriate button.
As the user, I should be able to see the classes during a selected day throughout the month.
As the user, I should be able to see all of the locations of Surge Gym on the map.
As the user, I should be able to see the different trainers and book the selected trainer.
As the user, I should be able to see all of the partners of the gym.
As the user, I should be able to reset my password despite being logged in.
As the user, I should receive an email when resetting my password.
As the user, I should receive a notification when resetting my password.
As the user, I should be able to log out whenever I want to.


### Test cases
Numerous manual testing were performed such as making sure the intents were properly
loading, that the login flow and the register flow were working correctly. The application was
tested on different emulators and api versions. Four test cases were developed to test various
functions of the application. The first test case tested the input fields of the login activity. The
second test case tested the input fields of the sign up activities. The third test case tested if the
randomMemberNo() function returned a random integer at least 2 times. And finally, the fourth
test case tested if the randomPassword() function returned a random integer at least 2 times.
More automated testing was preferred, however a lot of the functionalities were in fragments,
and we did not know how to perform tests on isolated fragments. In the future, acquiring this
knowledge will go a long way in making sure all the functionalities of the application are working.

### Individual’s role and responsibilities
The work was split up by functionalities and activities. Matthew built the Landing Activity, Login
Activity, the 2 Sign Up Activities, the Home Activity, the Location Activity, and the Payment
Activity. William built the Classes Activity, the Trainers Activity, the Password Forget Activities
and the Partners Activity. Matthew focused on the UI/UX development: building the navigation
bar, building the fragments and ensuring all the intents and the activity flow was flawless.
William focused on the database and login/logout functionalities with Firebase, Facebook and
Google. Matthew also developed an algorithm that turns the current user id as a Qr Code.
William also developed a recycler view to show the partners of the gym. In conclusion, the
workload was split 50/50.
Activity Screenshots
