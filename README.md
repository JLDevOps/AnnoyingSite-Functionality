# AnnoyingSite-Functionality
---
Code, templating and the Javascript functionality analysis of Feross Aboukhadijeh's The Annoying Site.

Link below redirects to The Annoying Site, but be careful when entering the site.  The site currently utilizes malicious javascript functions. 
**Click at your own risk: [Click Here](https://theannoyingsite.com)**

#### Example Functionality:
* Spawn smaller windows to bounce around the user's screen
* Vibrate a user's mobile device
* Download files onto a user's device
* Play videos on smaller windows
* etc. (more "annoying" functions)


## Inspiration
---
This project was inspired by Feross's talk on ["The Power of the Web Platform."](https://www.youtube.com/watch?v=6pY9Bfwfj2A)  
You can also view the Feross Aboukhadijeh's repository [here](https://github.com/feross/TheAnnoyingSite.com/). 

## Templating & Functionality
---
Templates have been created depending on the use of the Javascript functions that were used on the Annoying Site

A basic template has been created as an entry point to fill in with more Javascript functions, however several templates have been created with specific functionality (found in the Functionality Scripts folder).

More functionality scripts and Javascripts functions will be added to make more "annoying" features.

## Getting Started
---
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
A list of packages and software needed to be installed before testing:
1. Node
2. NPM

### Setting Up the Environment

After cloning or downloading the project on your own local machine:

Go into the **AnnoyingSite-Directory**.
```
cd AnnoyingSite-Directory
```
Then install the necessary npm packages via this command:
```
npm install
```
(Make sure there is a package.json file in the current directory)
The npm command will install the **ecstatic** package.

## Usage
---
Run the project, only after following the setup guide.

### Running

Go into the **AnnoyingSite-Directory**.
```
cd AnnoyingSite-Directory
```
Then install the necessary npm packages via this command:
```
npm start
``` 

The start command will provide a localhost IP where you can go to, to test out the sites Javascript functions.

### Running Different Functionality Scripts

If you want to try out different scripts instead of the main one, you will need to switch out the index.js file (found in the static directory) with another functionality Javascript file.

#### Example:
Usage of the Mobility Functionality File (**mobile-functionalities.js**):

Assuming that the current directory is in the main project directory.

Remove the index.js file form the **Annoying-Site-Directory**:
```
rm /Annoying-Site-Directory/index.js
```

Copy over the **mobile-functionalities.js** to the **Annoying-Site-Directory** and rename it to **index.js**:
```
cp /Functionality\ \Scripts/mobile-functionalities.js /Annoying-Site-Directory/static/index.js
```

Then go into the **AnnoyingSite-Directory** and run
```
npm start
```

## Acknowledgments
Thanks to Feross Aboukhadijeh for inspiring this project.  His additional work can be found here: **[feross](https://github.com/feross/)**
