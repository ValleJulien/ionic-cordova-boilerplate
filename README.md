# Ionic-cordova-boilerplate
A simple boilerplate for ionic framework (with angularjs) bootstraping cordova  
------------------------------------------------------------------------------

# To Start The Project
1. clone the repo and make sure you have nodejs `node -v`, if not on go here : `https://nodejs.org/en/`
2. then install cordova (linux command, for windows use git bash to use linux command): `sudo npm install -g cordova`
3. install ionic `sudo npm install -g ionic`
4. install bower globally if not `npm install -g bower`
5. install ng cordova throught bower `bower install ngCordova`

# If all are already installed
1. first clone the project
2. `npm install`
3. `bower install ngCordova`

# Create a ionic project
. `ionic start <yourProjectName> blank`

# Add some plugins
. `ionic plugin add cordova-plugin-vibration` (just an example)

# Lauch ionic server
. `ionic serve -l`

# Configure Platforms
. `ionic platform add ios` 
. `ionic platform add android` 

# Test it out
. `ionic build ios`
. `ionic emulate ios`

# Starting your own app
. just follow the guide here `http://ionicframework.com/docs/guide/starting.html`

# Use Ionci view on your device
. to test your app on ionic view `ionic upload`, make sure you have donwloaded ionic view app on your device (`http://view.ionic.io/`)
