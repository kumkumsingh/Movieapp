MoviesApp
A React Native application
Table of Contents
Functionality
Features
Installation
Setup of Android Emulator
Setup in Android Phone
Setup of the project

App Functionality
The App displays popular Movies and Tv series. When a Movie is selected, the app shows the details of the Movies.
The App also includes a Search Functionality which allows to Search for Movies.

Home Page - Features
Display the latest TV
Display Poupular Movies
Display Popular TV
Search Movies
Search Page - Features
Search bar
List of data
Button for navigation to HomePage
Detail Page - Features
Image of the selected item
Title
Overview (A short Description)
Rating.

Installation and running the application.

Setup the android emulator.
Go to the link specified, go to react native CLI Quickstart and perform all the instructions till setting up ANDROID_HOME

(https://facebook.github.io/react-native/docs/getting-started)

Install Android Studio, open the AVD Manager.

Select the type of phone.

Download the version of Android.

Click Finish. It opens a window. Select the play button displayed.

The emulator will open.


Setup in android phone
Connect mobile phone with USB cable.

Check the box to transfer files.

Go to Settings => Developer Options => Enable USB Debugging.


Setup of the project
Sign up and get the api key for the movie Database using the given link

(https://www.themoviedb.org/account/signup)

Clone the application by using the following command

git clone https://github.com/nirustanite/MoviesApp.git

cd to the folder MoviesApp/MovieApp.

cd MoviesApp/MovieApp

Install dependencies using this command

npm i

Open the constants file and change the api_key with your API_KEY. Save the file

Type the command to install the app

react-native run-android

Close the application in the emulator or phone.

Type the command to start the app

react-native start

When loading dependecy graph is done, open the app.

Now, the app can be used in the phone.
