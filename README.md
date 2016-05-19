# Electron - Desktop Applications (quick start)
**Electron (http://electron.atom.io/)**

## Install > Deploy
**Install/clone Git, Nodejs**

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/electron/electron-quick-start
# Go into the repository
cd electron-quick-start
# Install dependencies and run the app
npm install && npm start
```

**Go to your project folder**

cd /Users/matthijs/Documents/GitHub/socialbrothers


**Install your program**

npm install


**Start your program**

npm start


**Install the electron packager in your folder so you can create your build**

npm install electron-packager


**Add this piece of code to your package json file**

```bash
"name": "SocialBrothers",
"productName": "Social Brothers",
"scripts": {
  "build": "electron-packager . --all"
},
```
Or for you win45 program map only + an icon from your build folder
```bash
"name": "SocialBrothers",
"productName": "Social Brothers",
"scripts": {
  "build": "build"
},
"build": {
  "win": {
    "iconUrl": "https://assets-cdn.github.com/favicon.ico"
  }
},
```

**Create the build**

npm run build


**Create the setup file (windows)**

Download: http://installforge.net/download/

Open and create setup with Installforge


**Create the DMG file (mac os)**

Following soon

## Extra information
- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start).

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

Cool library's: http://socket.io / https://www.npmjs.com/
Function of electron: http://electron.atom.io/docs/api/web-contents/







