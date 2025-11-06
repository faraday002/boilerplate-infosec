# Information Security with HelmetJS - FreeCodeCamp Project

## Overview
This is a FreeCodeCamp educational project for learning Information Security with HelmetJS. The project provides a boilerplate application where students complete security challenges by implementing various helmet middleware configurations.

## Project Structure
- **myApp.js** - Main application entry point with Express server and helmet configuration space
- **server.js** - Verification system for FreeCodeCamp challenges (DO NOT EDIT)
- **views/index.html** - Frontend HTML page
- **public/style.css** - Styling for the frontend
- **package.json** - Node.js dependencies (Express, Helmet)

## Recent Changes (November 6, 2025)
- Imported project from GitHub
- Configured for Replit environment:
  - Updated server to listen on port 5000 with host 0.0.0.0
  - Set up workflow for automatic server start
  - Configured deployment settings for autoscale deployment
  - Installed all npm dependencies

## Technical Details
- **Language**: Node.js
- **Framework**: Express.js
- **Security Library**: Helmet.js (v3.21.3)
- **Port**: 5000 (configured for Replit)
- **Host**: 0.0.0.0 (required for Replit proxy)

## Running the Project
The project automatically starts when you run the Repl. The workflow is configured to run:
```
npm start
```

This executes `node myApp.js` which starts the Express server on port 5000.

## Deployment
The project is configured for autoscale deployment, which is suitable for this stateless web application. To publish the app, use the Replit publish button.

## Learning Resources
Instructions for completing the HelmetJS challenges can be found at:
https://www.freecodecamp.org/learn/information-security/information-security-with-helmetjs/

## Notes
- The server.js file should NOT be edited as it contains the FreeCodeCamp verification system
- Students should implement helmet middleware in the myApp.js file between the imports and the export statement
- The application includes CORS headers and file serving endpoints for the verification system
