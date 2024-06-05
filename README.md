This project is a simple Android application that fetches and displays weather information of the current location using the OpenWeatherMap API. 
The users can enter the current location, and the app will show the current temperature, humidity, and weather description.
Additionally, the application retrieves and displays geographic information such as latitude, longitude, and a geocoded address (country, state, and city) based on the coordinates of the searched city.

The main features are,

1.Fetch current weather data from OpenWeatherMap API.
2.Display current location, current time, latitude, and longitude.
3.Fetch and display geocoded address (country, state, city) based on coordinates.
4.Update weather data dynamically based on user input.



Project Structure

1.MainActivity.java
This is the main activity of the application, responsible for fetching and displaying weather data.

DownloadJSON Class: An AsyncTask to fetch weather data from the API.
Loading Method: Handles the user input, makes API calls, and updates the UI.


2.activity_main.xml
This is the main layout file, defining the UI components.

RelativeLayout: Main container layout.
EditText: Input field for the city name.
Button: Button to trigger the weather data fetch.
TextViews: Display city name, time, temperature, humidity, and description, longitude, latitude,geocoded address.


3.AndroidManifest.xml
Defines the necessary permissions and main activity.

INTERNET Permission: Required for making network requests.



Setup instructions

Prerequisites are,
1.Android Studio
2.API key from OpenWeatherMap (2315437a225a1268ac2135ee4f11fa2d)



Steps

1.Clone the repository

2.Open the project in android studio

Launch android studio
Select 'file>open> and navigate to the cloned repository directory.
Open the project

3.Add API key

Open MainActivity.java file
Replace the API key with the user own API key from OpenWeatherMap.

String key = "2315437a225a1268ac2135ee4f11fa2d";

4.Run the Application

Connect user Android device or start an emulator. 
Click on the Run button in Android Studio.



How to use,
1.Enter the current location in the EditText field.
2.Click the "Enter" button.
3.The application will fetch and display the weather data and geocoded address for the specified location.


