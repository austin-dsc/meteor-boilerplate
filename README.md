meteor-boilerplate
==================

a simple meteor boilerplate app using scss

## Setup

### Install NodeJS

NodeJS is the "backend" for your website. It is was serves up the images, javascript files, and any other assets whenever someone visits your site.

NodeJS runs on the same engine as Chrome's javascript, so it is fast, stable, and you don't need to learn another language.

[Install NodeJS](http://nodejs.org/)

### Install Meteor

Meteor is an application framework that solves all of the difficult problems for you so that you can focus on building your app.

Meteor is written purely in javascript and includes a lot of tools that you would normally have to setup yourself.

It is definitely worth your time to learn Meteor, it will let you skip years ahead and begin writing professional quality apps sooner.

Meteor also support iOS and Android, so once you are ready you can start writing mobile apps with it too.

[Install Meteor](https://www.meteor.com/install)

### Clone Git Repo

A git repo is like a save file for you project. It lets you work without worrying about breaking something you already did, and is hands down the most important thing for a developer to know and use.

Having your project under version control lets you move forwards and backwards through working commits, and create new "branches" when you want to start working on some other feature.

To clone the git repo for this project :

1. Open terminal
2. `cd` into your workspace directory
3. `git clone` this repo url

### Install Ungit

Now that you have a git repo for this project, you need a tool to manage it. You can do everything you need from the command line, but it can be confusing and I recommend using ungit instead.

[Ungit Official Site](https://github.com/FredrikNoren/ungit)

Ungit is installed as an "npm" package. "npm" stands for Node Package Manager, and it allows you to install tiny packages that are basically stand alone apps that run on NodeJS.

There are THOUSANDS of npm packages out there, so before you try to create something yourself check to see if a package already exists for your problem.

[NPM Registry](https://www.npmjs.org/)

To install Ungit :

1. `npm install -g ungit`

Note : If it prompts you for a password your npm and node in installed improperly, try reinstalling.

### Start Meteor App

Now that you have cloned your app, its time to start it and get to work.

To start the Meteor app :

1. `cd` into the app root
2. `meteor run`
3. open your browser and to to `http://localhost:3000`

This is where Meteor is serving your local version of the app, no one else can see this. As you develop meteor will rebuild the app and autorefresh this page for you.

### Deploy Meteor App

Once you are ready to deploy your app ( to test it on your phone for example ), all you need to do is :

1. `cd` into the app root
2. `meteor deploy <your-app-domain>.meteor.com`

Note: If it asks you for your meteor account you may have to set one up at [Meteor.com](https://www.meteor.com/)

Deploying to meteor.com is great for testing and prototyping, but not for actual production. Meteor will shut down the server every 15 minutes if there are no visitors.

Once you are ready to deploy to a real server I can go into more detail.

### Meteor App Structure

#### TODO
