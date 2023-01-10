# Braxton M | UCBC11_PWA Text Editor | README

The goal of the PWA Text Editor was to take an exisiting project and implement a webpack that would allow for scripts, design, and 
imagery to populate the page using the process of cached assets. This allowed a more thorough understanding of webpack's and 
installation prompts for general use. It also gave general expousre to using the client and server side folders.

Main issues would include clearing the console cache of old data that was preventing it from being installed a second time. 
Another issue was having `nod_modules` exist while being within `.gitignore` in all three areas of the project to 
allow it to run smoothly.


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

To start the server, you will need to run `npm install` and `cd server && npm i && cd ../client && npm i` to install dependencies. 

The user will then need to run `npm run build` and `npm start` for the production build and `npm start dev` for the development build.


## Screenshot

Screenshot of the Application

* Screenshot 1: Alert requesting installation of J.A.T.E

![App Screenshot](/assets/screenshot1)

* Screenshot 2: J.A.T.E window

![App Screenshot](/assets/screenshot2.JPG)

## Links

- [Heroku Live Deployment](https://ucbc19-texteditor.herokuapp.com/)
- [Github Project Repository](https://github.com/BrackyM/UCBC19_PWATextEditor)


##  Contributors / Resouces Used
    
UC Berkley Activites

Sky Texier - [Github](https://github.com/skytexier)

 - Helped me with issues within script commands and Heroku deployment errors