# Project information
**Project name :** ‘Weather-app’
**Description :** Building a weather app with a user-friendly layout and detailed weather updates. The app displays current weather, temperature, sunrise/sunset times, humidity, wind speed, and a three-day forecast. This project utilized dummy data for weather information.

## Project Objective 
To create a real-time weather application that retrieves the user's precise location and provides weather forecast for the day and upcoming days also.We also tried to design a simple but visual UI that provides comprehensive data. 

## Folder and file
In this project create folder and files -
- assets folder - In this folder, all images have filenames with extensions such as .png, .jpg, .svg, and .webp.
- index.js file - In this file, JavaScript code is written for the hamburger icon, weather dummy data. 
- index.html file - In this file write all html code (navigation bar, Our Team, About Project, Login/Signup page, and Footer Section)
- login-signup.css file - In this file, all CSS for the login/signup page is written.
- style.css file : In this file write all css code (navigation bar, Our Team, About Project, Login/Signup page, and Footer Section)

## Weather dummyData Features
1. Current Weather Information:
  	- Current weather conditions for a specific location at any given time.
2. Current Temperature:
   	- The current temperature at the specified location.
3. Sunrise Time:
  	- The time at which the sun rises at the specified location.
4. Sunset Time:
   	- The time at which the sun sets at the specified location.
5. Humidity:
   	- The amount of moisture present in the air at the specified location.
6. Wind Speed:
    - The speed of the wind at the specified location.
7. Next Three Days Weather Information:
    - Weather forecast for the upcoming three days at the specified location.

### Example
  {
    location: "Agra", sunrise: "06:16am", sunset: "6:31pm", temperature: "12°C", humidity: "3%", windspeed: "5km/h", dayData: [
      { day: "Sun", weatherIcon: "https://themesfamily.com/2024/mugni/assets/img/icon/1.png", temperature: "15°" },
      { day: "Mon", weatherIcon: "https://themesfamily.com/2024/mugni/assets/img/icon/2.png", temperature: "3°" },
      { day: "Tue", weatherIcon: "https://themesfamily.com/2024/mugni/assets/img/icon/3.png", temperature: "10°" }
    ]
  }


## Navigation Bar
In the navigation bar, add additional navigation options 
- Home : If a user clicks on the 'Home' navigation link, the webpage automatically moves to the Home page.
- Our Team : If a user clicks on the 'Our Team' navigation link, they will be directed to the Our Team section, where they can find comprehensive information about our team. This includes details about each team member and the specific features they have built in the weather app .
- About project : If a user clicks on the 'About Project' navigation link, they will be directed to the About Project section, where information about the project is provided.
- Login : If a user clicks on the 'Login' navigation link, upon clicking the login button, open the modal login page. 
- Signup : If a user clicks on the 'Signup' navigation link, upon clicking the login button, open the modal signup page .
- Profile Icon : If a user clicks on the profile icon, they will be redirected to the "Our Team" section.


## Searching weather data
By default, data for a specific location is shown on the main page. When a user searches for data of a particular location, the default data is replaced with the searched data.

**By default show weather data**
![Image](https://ibb.co/L8v8W4D)

**After searching show weather data**
![Image](https://ibb.co/jLyBvtG)


## Details of the HTML Code
The code for the navigation bar, Our Team, About Project, Login/Signup page, and Footer Section is written on the index.html(main file).

## CSS styling
Two files have been created for CSS styling.
    - first is named style.css.
    - second is named login-signup.css.
The style.css file contains CSS for the navigation bar, our team section, about project section, and footer section.
The CSS for the login/signup page is written in the login-signup.css file.

## Media Query
In this project, include media queries for small, medium, and large mobile screens, tablet screens, and laptop screens.
- Mobile screen media query sizes
    - 320px for small screens
    - 375px for medium screens
    - 425px for large screens
        - Hamburger icon work on only mobile screen size(small, medium, large) 
- Tablet screen media query size
    - 768px
- Laptop screen media query sizes
    - 1024px for small screens
    - 1440px for large screens
