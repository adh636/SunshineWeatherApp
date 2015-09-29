# SunshineWeatherApp

This app was built in conjunction with Udacity's Developing Android Apps class.  The final source code was pulled from their github repository at the end of the course.  Most of the code was worked on in different exercises throughout the course.

Below are the paths to navigate to the most relevant code, including some explanation of what the code is.

# SunshineWeatherApp/app/src/main/java/com/example/android/sunshine/app

This folder includes a majority of the .java files.  MainActivity.java is what launches when the app is opened.  This calls ForecastFragment.java to display the weather forecast.  SettingsActivity.java controls the settings menu where you can choose your location and launch the maps app to view the selected location.  DetailActivity.java and DetailFragment.java handle the forecast detail activity when you select a specific day from the ForecastFragment.

# SunshineWeatherApp/app/src/main/java/com/example/android/sunshine/app/data

This holds the database files and helpers for the weather app.  It pulls data from an API and uses JSON to format and pass the data to an SQLite database.  This data is then used by the different fragments.

# SunshineWeatherApp/app/src/main/res

This folder holds all the resource xml files.  This is where the layout and value files are stored.  The layout files determine the UI of the app for the different activities and fragments.
