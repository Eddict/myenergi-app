# myenergi-app

## Backend

A java spring boot backend to access myenergi data.
A cron-job will scrape and persist data into a database.

 * [demo on heroku](https://myenergi-native.herokuapp.com/zappi)
 * [readme backend](backend/README.md)

Application hosted as Spring Native image on heroku. Heroku puts my container to sleep when it's not been used for 30 minutes. Using a native image reduces the startup time significantly

## Frontend 

An angular frontend that connects to the Java spring boot application.
Easily and quickly access historical data. E.g. yearly overview of how much KWh is used to charge your EV.


 * [demo on netlify](https://myenergi.netlify.app/)
 * [readme frontend](frontend/README.md)
