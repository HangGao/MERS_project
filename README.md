# Picture Sharer

This repository presents an full-stack MERN-based Single Page App (SPA) that uses **React.js**, **Node.js**, **Express.js** and **Mongodb** to allow users to share places of interest. It supports both **authenticatoin** and **authorization**, as well as both browser and mobile views.

## Features
1. Register as a new user. 
2. Share a place as a login user with the coordinates of the place automatically generated by Google Geocoding API. 
3. View the place on Google map. 
4. Modify and delete the place shared.
5. View other users' shared places.

## Installation
1. Download the repository. 
2. Change the configuration file "nodemon.js" in the backend folder, setting all configuration keys with your values. 
3. Change the configuration file ".env" in the frontend folder, setting all configuration keys with your values. 
4. Run `npm install` in the backend folder to install all the dependencies.
5. Run `npm dev` in the backend folder to start the backend server.
6. Run `npm install` in the frontend folder to install all the dependencies.
7. Run `npm start` in the frontend folder to start the frontend server (static files).
8. Visit the browser with the IP address you set for the frontend. 

Note that if you'd like to deploy the app, then you may have to go through your server provider's configuration guide and you may want to use `npm run build` to get the build version of the app.

## Demo

### User Interface

![user interface](../master/demo/main.PNG?raw=true)

### Registeration

![Registeration](../master/demo/register.PNG?raw=true)

### Add A Place

![Add A Place](../master/demo/adding_a_place.PNG?raw=true)

### View the Places

![View the Places](../master/demo/places.PNG?raw=true)

### View A Place on Google Map

![View A Place on Google Map](../master/demo/view_on_map.PNG?raw=true)
![View A Place on Google Map](../master/demo/view_on_map2.PNG?raw=true)

### Modify A Place
![Modify A Place](../master/demo/edit_place.PNG?raw=true)


### Delete A Place
![Delete A Place](../master/demo/delete_place_1.PNG?raw=true)

### Sample Error Handling
![Delete A Place](../master/demo/no_place_found.PNG?raw=true)
![Delete A Place](../master/demo/no_place_found_2.PNG?raw=true)