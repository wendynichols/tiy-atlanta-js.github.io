---
layout: page
title: Tools
---

## Basics

#### [OSX Mavericks](https://www.apple.com/osx/)

Everyone is required to use a Mac computer and the latest version of OSX.

#### [Google Chrome](https://www.google.com/intl/en/chrome/browser/)

There are a few good browsers out there, but in this class we'll be focusing on using Chrome. With it's built in dev tools you can't go wrong.

#### [XCode Command Line Tools](https://developer.apple.com/xcode/)

* Go to the Apple Developer Downloads site.
* Sign in with you Apple ID.
* Search for "Command Line Tools (OS X Mavericks) for Xcode - April 2014."
* Download the ".dmg" file for that package to your Desktop. 
* Once downloaded, double-click on the file to unpack it.
* Double-click on the file called "Command Line Tools (OS X 10.9).pkg." and complete the guided installation instructions.

#### [iTerm 2](http://www.iterm2.com/)

This is an excellent replacement for Apple's built in terminal.

* Download & Install

#### [Oh My ZSH](http://ohmyz.sh/)

This makes your terminal (iTerm 2) come alive.

* Open up iTerm 2 (or terminal)
* Run this command `curl -L http://install.ohmyz.sh | sh`
* Restart your terminal program
* For more information, read through their documentation


#### [Homebrew](http://brew.sh/)

A package manager for installing developmental tools onto your Apple computer.

* Open up Terminal.app (Applications > Utilities > Terminal)
* Type the following command: 
`ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"`
* Follow the instructions on-screen.
* When finished, run `brew doctor`.


#### [Git](http://git-scm.com/)

This is the version control software of choice that we will be using

* Open terminal
* Run `brew install git`

To get up to speed I would suggest walking through the [Learn Git](https://try.github.io) tutorial.

#### [Github](http://github.com)

The web-bases service we will be using to store all of your work.

* Sign up for an account.

#### [Creating an SSH Key](https://help.github.com/articles/generating-ssh-keys)

You'll need an SSH key when using Github. SSH keys are a way to identify trusted computers, without involving passwords. Walk through the steps in this [tutorial](https://help.github.com/articles/generating-ssh-keys) to create your SSH key and add it to your Github account.

#### [Sublime Text 3](https://www.sublimetext.com/3)

* Download & Install
* Install [Package Manager](https://sublime.wbond.net/) - Follow the directions

!! NOTE !! - This software is free to use while in class but after you finish we strongly recommend you purchase a license. After all if you built a piece of software, wouldn't you want to be paid for it?

You can also check out [Atom](atom.io), which is a very similar and completely free text editor.

#### [Node](http://nodejs.org/) & [NPM](https://www.npmjs.org/)

Node.js is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications. 

* Open up terminal
* Run `brew install node`

Node Package Manager (NPM) comes installed with Node. If you followed the above you'll have it installed. Let's check to make sure.

* Open up terminal
* Run `npm help`

You should see a list of help commands. If you get an error, make sure you installed Node first.

#### [SASS](http://sass-lang.com/)

Sass is the most mature, stable, and powerful professional grade CSS extension language in the world.

Let's install it

* Open up terminal
* Run `gem install sass`
* Run `sass -v` to verify it's installed.

!! NOTE !! If you get a permissions error when installing Sass or any Ruby Gem for that matter, add the word `sudo` before your command. In this case it would be `sudo gem install sass`.

## Development Tools

#### [Yeoman](http://yeoman.io/)

A web scaffolding tool that we will use to rapidly create our projects.

* Open terminal
* Run `npm install -g yo`

#### [Bower](http://bower.io/)

A dependencies manager for the web. This helps us manages the different JS & CSS libraries we will use.

This comes installed with Yeoman

#### [Gulp](http://gulpjs.com/)

This is a the build tool we will be using to build our projects. We will also use this to compile our SASS and even deploy to Github Pages.

* Open terminal
* Run `npm install -g gulp`

#### [Custom TIY Yeoman Generator](https://github.com/twhitacre/generator-tiy-webapp)

I built this to ease the introduction to the above tools. It uses gulp and adds a few custom libraries that we will use over time.

* Open terminal
* Run `npm install -g generator-tiy-webapp`


## Other Tools

#### [Screenhero](http://screenhero.com)

Screenhero is an interactive screen sharing application. It will allow me to assist you when we are not in the same room. We might also use it during class for homework review.

Make sure to add `tim@theironyard.com`.