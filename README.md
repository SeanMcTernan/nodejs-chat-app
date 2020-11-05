# NodeJS Chat App <a href="https://github.com/SeanMcTernan" target="_blank"><img src="https://raw.githubusercontent.com/SeanMcTernan/SeanMcTernan/140c9255ba95e71fc0988bc36cc1f327fe360b9f/ReadMe_Badge.svg" width="120"/></a>


<img src="https://raw.githubusercontent.com/SeanMcTernan/SeanMcTernan/8bbd1f099646363b32cc039953efc3cf1137dad8/nodejs_chat_app.svg" align="right"
     alt="NodeJS Chat App Image By Sean Mc Ternan " width="120" height="178">

A small NodeJS chat app designed to explore Socket.io and how it can be used to update information in real time on a user's browser. 

## Technologies Used
| Name                                                        | Purpose                                                                                                    |
| ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [NodeJS](https://nodejs.org/en/)         | Main programming language for the project |
| [socket.io](https://socket.io/)                      | To handle chat messages in real time |
| [Express.js](https://expressjs.com/)                            | To run the web server |
| [NPM](https://www.npmjs.com/)                                | As a package manager                                                         |
| [ENV-CMD](https://www.npmjs.com/package/env-cmd)                     | To set environment variables |                                                             
| [Bad-Words](https://www.npmjs.com/package/bad-words) | To help catch and censor bad words |
| [Nodemon](https://www.npmjs.com/package/nodemon) | Restart the app during development |                                                


### The App

<p align="center">
  <img src="https://github.com/SeanMcTernan/SeanMcTernan/blob/master/ReadMe_Images/nodeJS_Chat_App_ScreenShot_1.png?raw=true" alt="Chat App Login Page" width="738">
</p>

The app allows users to enter their name and the chat room they would like to enter. When entered, the app checks for a valid unique entry and stores the information entered. 

<p align="center">
  <img src="https://github.com/SeanMcTernan/SeanMcTernan/blob/master/ReadMe_Images/nodeJS_Chat_App_ScreenShot_2.png?raw=true" alt="Chat App Main Window" width="738">
</p>

In the window above, you can see two users logged into the app (one on a regular window, the other on Incognito). As new users log in or out, messages are displayed to those in the chat room on the activity of other users. 'User has joined', 'User has left' etc. Should a user use bad language the Bad-Language dependency will catch the phrase and the admin will send them a message informing them that 'Profanity is not allowed!'.

<p align="center">
  <img src="https://github.com/SeanMcTernan/SeanMcTernan/blob/master/ReadMe_Images/nodeJS_Chat_App_ScreenShot_3.png?raw=true" width="738">
</p>
Along with sending chat messages, users can share their location with others in the room. By hitting the 'Send Location' feature. The app takes their location and a link to Google Maps from the chat room. 
<p align="center">
  <img src="https://github.com/SeanMcTernan/SeanMcTernan/blob/master/ReadMe_Images/nodeJS_Chat_App_ScreenShot_Location.png?raw=true"User's location on a map" width="738">
</p>


### Install Instructions

1. Clone/Download the Repository 
2. From the folder run `npm install`
3. Run `npm start`

### Development Time: 1 Week

