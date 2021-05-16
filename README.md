# Plant Manager

Application developed for the Rocketseat's Next Level Week 5. The project consists of an app that helps to manage the caring for house plants notifying the user when it's due time to water each of it's plants.

![](https://imgur.com/WdaqWeA.png)
![](https://imgur.com/EiCSmWn.png)
![](https://imgur.com/RzerBpf.png)
![](https://imgur.com/NxnUJ4P.png)
![](https://imgur.com/yK38CE6.png)
![](https://imgur.com/eZSFkS5.png)
![](https://imgur.com/JwL52pt.png)
![](https://imgur.com/eLZRYHK.png)
![](https://imgur.com/55A10cV.png)
![](https://imgur.com/w8ToTkk.png)

## Getting Started and Installing

To run the project, you must first clone this repository to your machine and install the dependencies listed on the package.json file.

Run the commands below:

To install dependencies:
```
yarn
```

This project was built using the Expo SDK so after installation is complete, run the command below to start the project.
```
expo start
```
The project will open on the emulator or in your device if it is connected to the same network.

The project uses JSON server to mimic an Rest API and it must be initialized before using the app. At the terminal run: 
```
json-server ./src/services/server.json --host YOUR_HOST --port 3333
``` 

To determine what is your host, you can enter ipconfig on the terminal or check at the Expo screen after you start it.

## Using the app

When it loads the app will ask for the user name so it can be stored in the memory and then show a list of plants and a filter by locations where they may be placed. 

User can press on a plant, see tips to take good care of it and schedule a time for watering it, after doing this the app will notify the user's phone when it's time according to the plants own watering schedule.

On the bottom tab navigator the user can access a dashboard with it's registered plants and next schedule and can remove the plant from the list.


### Built with
This project was developed using React Native, Expo SDK, Typescript, Hooks and Functional Components, Axios to fetch to the API, Expo Notificatiosn for the notification messages, Expo Vector Icons for the Icons, Lottie React Native for the animated loading screen, Date FNS for dealing with dates and times.

## Credits
Designed by Rocketseat and developed by Paulo Lima, in May, 2021. 


