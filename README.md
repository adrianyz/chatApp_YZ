#chatApp_YZ

Build a stand-alone chat app using socket.io, that you can integrate into that project (or any other).

## Assignment Requirements:

* Use Node and socket.io to create an interactive chat application.
* Design an engaging skin for the application using HTML / CSS; add transitions / interesting micro transactions using a combination of JS and CSS (or you can use something like Greensock).
* Expand on the default functionality to include a notification message when a user joins or leaves the chat; use colour to differentiate between user messages; choose one other enhancement to implement ( refer to the documentation @ https://socket.io/ ).

## Detailed Requirements:
* Design the skin for the chat application per the assignment requirements.
* Create a repo / detailed readme for the project; use as many development branches
as you feel you need, but make sure everything is merged to the master branch when
you submit.
* Use Node / NPM / socket.io to create the assets / folder structure and
develop the app.
* Use Grunt or Gulp to compile and minify your production files (SCSS -> CSS, minified
JS file, other Grunt / Gulp based tooling like image optimization etc)


## Installing
### Installing NPM

```
npm install npm@latest -g
```

### Installing grunt
* Setup package.json
```
npm init
```
* Install Grunt CLI as global:
```
npm install -g grunt-cli
```

* Install Grunt in your local project:
```
npm install grunt --save-dev
```

### Installing sass
```
npm install grunt-contrib-sass --save-dev
```

### Installing socket.io

```
$ npm install socket.io
```

## Test

To test the application, in terminal type in
```
node app
```

the result will be running in localhost:3000
