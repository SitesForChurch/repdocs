
![](https://dl.dropboxusercontent.com/u/47159282/computer.jpeg)

If you are going to do this, you'll need the right tools.  

**YOU DON'T NEED AN EXPENSIVE COMPUTER TO DO THIS.** Any computer that can run the latest version of Google Chrome or Mozilla Firefox will be good enough.  You can even do all of this work on an inexpensive Chromebook.  

Just follow these four steps and you'll be good to go...

# A. Set Up Your Accounts

No matter how you choose to work, you'll need to have these three accounts set up:

![](https://dl.dropboxusercontent.com/u/47159282/GitHub.jpg)

## 1. Get a Github account.

Github is a free place to store code.  It's central to our process at Sitesfor.church. You must sign up for a free Github account at [https://github.com/join](https://github.com/join).


![](https://dl.dropboxusercontent.com/u/47159282/airtable.jpg)

## 2. Get an Airtable account.

[Airtable](http://airtable.com) is an online database platform that serves as the content management system for our sites.  [Get a free account](http://airtable.com), and get to know this product because you are going to be working in it and helping others work in it.

![](https://dl.dropboxusercontent.com/u/47159282/nitrous.png)

## 3. Get a Nitrous account.

Nitrous is an online Internet Development Environment (IDE).  Essentially, it's a portal to an online computer running all of the software you'll need to setup sitesfor.church sites.  It also allows us to see what you are seeing, which is invaluable for helping you through problems. 

You'll need to sign up for a [free nitrous account](http://nitrous.io).

![](https://dl.dropboxusercontent.com/u/47159282/slack.png)

## 4. Get a Slack account.

Slack is a communication platform that we use to send out messages and communicate internally.  The account is free.  You'll get a slack invite via email.


# B. Launch the Quickstart (Nitrous)

For most people, we recommend using Nitrous.  Just by pressing the button below, you'll get a development environment in the cloud with all of the tools you need installed and the files already ready to go.  

You can also use Nitrous to collaborate - when you need help Ryan or Alex can jump on with you and you can watch them code in real time on your screen. To use Nitrous for the first time, just **PRESS THE BUTTON BELOW.**

[![Nitrous Quickstart](https://nitrous-image-icons.s3.amazonaws.com/quickstart.svg)](https://www.nitrous.io/quickstart?repo=https://github.com/SitesForChurch/master-theme.git)
----
Here is an explanation of how it works.

<iframe width="560" height="315" src="https://www.youtube.com/embed/4dKwt_j1b0Q" frameborder="0" allowfullscreen></iframe>

> At any point - you can run `Run > Start Server` and then `Preview > 30000`


# C. (Advanced Users Only) Working Locally 

Nitrous offers all the tooling you need to get started as a site-rep with sitesfor.church.  You'll never need anymore more than Nitrous, so the rest of this is **strictly optional**.  

After you have done several sites, you may want to move your process from the cloud to your own computer.  The steps for that will vary based on what kind of computer you have.  

## On A Mac or Linux

You need to have the following installed:

* Git (not to be confused with github). 
    - On a mac you must install the command line tools. (You can find a tutorial [here](http://railsapps.github.io/xcode-command-line-tools.html))
    - On linux run `sudo apt-get install git` from the command line.
* Ruby (This is installed on a mac by default - on linux run `sudo apt-get install ruby`).  You can check if it's installed by running `ruby -v` on the command line.
* Jekyll - A ruby based static site generator.  You get it by running `gem install jekyll` after you confirm that ruby is installed.
* Node - Download the installer at [nodejs.org](https://nodejs.org/en/).

Once these three are installed, you'll have to clone the [master-theme repo](https://github.com/SitesForChurch/master-theme) from github, and then run the following commands:

* `npm install` - This will install the local dependencies that don't come bundled in the repository.
* `bower install` - This installs more dependencies that npm doesn't cover.

That's it.  You can now edit the files using whatever text editor you want on your computer (I like Sublime Text - but atom and visual studio code are both great too.)  

## On Windows

Windows is a little more tricky.  It's not a friendly environment for the open source development tools that make up the modern web.  [They are working on fixing that](http://arstechnica.com/information-technology/2016/04/why-microsoft-needed-to-make-windows-run-linux-software/) through and a planned update to Windows 10 this summer is going to include linux command line tools.  When that update ships, we'll update this with instructions for windows too.



