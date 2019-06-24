### Demo page
Hosting by firebase: https://bug-ios-sw.firebaseapp.com/

### Deployment

- Clone this repository

- Run the script in project folder
`npm install`

- Enter in `package.json` and change the `homepage` config to new app url (suggestion for hosting: firebaseapp.com)

- Run the script for build:
`npm run build`

- Publish the `build` folder in your preferred hosting


For the more information for the deployment app in firebase, read https://facebook.github.io/create-react-app/docs/deployment#firebase-https-firebasegooglecom


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


### Steps to simulate bug
1) Open the site in browser or if is mobile, install the PWA APP

2) After the open the site, execute the next steps for publish `new version` of the app

3) Change any html/text in `src/App.js`

4) `npm run build` for build the current change

5) Deploy app in your preferred hosting

6) Open the site (If it is open, press F5)
If is PWA app, close and open the PWA app

7) After reload page, a new version of the service worker (app) is launch in browser

8) After install the new service worker, a dialog confirmation is open for user accept the upgrade new app version

9) After the confirm dialog, the app is reload with new version


*In iOS steps 6 and 7 do not happen*