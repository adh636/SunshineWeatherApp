# SunshineWeatherApp

This app was built in conjunction with Udacity's Developing Android Apps course I recently completed.  The final source code was pulled from their github repository.  Most of the code was worked on in different exercises throughout the course.

Below are links to navigate to the most relevant files, including some explanation of what the code included in the files do.

https://github.com/adh636/SunshineWeatherApp/tree/master/app/src/main/java/com/example/android/sunshine/app

This folder includes a majority of the .java files.  MainActivity is what launches when the app is opened.  This calls ForecastFragment to display the weather forecast.  SettingsActivity controls the settings menu where you can choose your location and launch the maps app to view the selected location.  DetailActivity and DetailFragment handle the forecast detail activity when you select a specific day from the ForecastFragment.

https://github.com/adh636/SunshineWeatherApp/tree/master/app/src/main/java/com/example/android/sunshine/app/data

This holds the database files and helpers for the weather app.  It pulls data from an API and uses JSON to format and pass the data to an SQLite database.  This data is then used by the different fragments.

https://github.com/adh636/SunshineWeatherApp/tree/master/app/src/main/res

This folder holds all the resource xml files.  This is where the layout and value files are stored.  The layout files determine the UI of the app for the different activities and fragments.

# Screenshots

WeekView

![weekview](https://cloud.githubusercontent.com/assets/12743215/12214542/17c1cf62-b666-11e5-9fc1-38fc78642361.jpg)

DayView

![dayview](https://cloud.githubusercontent.com/assets/12743215/12214543/19a5c964-b666-11e5-9e72-a53df5f29297.jpg)

SettingsView

![settingsview](https://cloud.githubusercontent.com/assets/12743215/12214545/1af6bc4c-b666-11e5-8686-009004052082.jpg)
