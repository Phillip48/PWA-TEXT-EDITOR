# PWA-TEXT-EDITOR  
  
## Table of contents    
-[Description](#Description)   
-[Installation](#Installation)  
-[Contact Me](#Contact-Me)    
-[License](#License)  
-[Contributors](#Contributors)  

## Description  
This app is a text editor that runs in the browser. The app is a single-page application. It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application can also function offline.  
[Live Link](https://dry-inlet-40544.herokuapp.com/)  

## The Project
```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```  

## Acceptance Criteria  
  
```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```  

## Installation  

You can access the deployed application with the Heroku link: heroku

To install the project follow these steps:

1. Clone the application from GitHub with:

   - `git clone`

2. From the root folder, install the dependencies with:

   - npm i

3. Run the app with:
   - node server.js 

## Contact Me  
Github: Phillip48  
Email: phillip482@icloud.com  

## License
This project is licensed under MIT.

## Contributors  
*Phillip48*  
