
![](https://dl.dropboxusercontent.com/u/47159282/computer.jpeg)
  
## First - the Gauntlet 

In order to be a site-rep, you have to have the right tools setup on your computer.  This isn’t an easy task, but it’s pretty well documented on the Internet.

> **NOTE: YOU DON'T NEED AN EXPENSIVE COMPUTER TO DO THIS.** Any computer that can run the latest version of Google Chrome or Mozilla Firefox will be good enough.  You could even use cloud software like nitrous.io on a chromebook (although that will complicate the setup a little more.)


I’m not going to walk you through setting these up for two reasons:

1. **Because it’s different on everyone’s computer.**  It’s going to be a slightly different process for each operating system (Mac, Windows, Linux) and it may even be slightly different for the versions of the operating system (i.e. Windows 8 vs Windows 10)
2. **Because if you can’t figure this stuff out, then you aren’t ready to be a site-rep.**  Installing this is going to require using the command line, researching on the internet, following instructions and paying attention to detail.  I can’t teach you how to do these things.  But I can tell you that if you can figure this stuff out, then the rest of this stuff will be easy for you.

Here are the things you need to do before you move on:

1. Install [Microsoft Visual Studio Code](https://code.visualstudio.com).
2. Setup a [github account](http://github.com) and install [github desktop](https://desktop.github.com/).
3. Install [Jekyll](http://jekyllrb.com) on your computer. 

    ![Jekyll](http://sitesforchurch.s3.amazonaws.com/logo-2x.png)

    **Jekyll is the command line tool that builds our websites**.  It’s the backbone of what we do.  Depending on your operating system, it can be hard to install.  A good starting point is the [jekyll website](http://jekyllrb.com/docs/installation/).  Basically, you are going to need to have the right version of Ruby on your computer and then it’s easy from there.

    *This will most likely involve installing a different version of ruby and may require some other downloads.*  It’s by far the trickiest part of this whole gauntlet.  Just take your time, do a lot of google searches and you will get it.  

4. Install [Nodejs](https://nodejs.org/en/) and NPM on your computer (latest version).
5. Install the following nodejs dependencies globally:

    * Browser-sync `npm install -g browser-sync`
    * Node-sass `npm install -g node-sass`
    * Bower `npm install -g bower`


<hr>

**After you have these successfuly installed on your computer, send me an email at sitesforchurch@gmail.com.**

<hr>

> **One more thing that isn't required but will make your life easier:**
> Consider adding the following aliases to bottom of your `.bashrc` or `.zshrch` file (on mac or linux):

```bash
alias data="node _airtable.js"
alias build="jekyll build"
alias sass="node-sass _css/ -o _site/assets/css/ -wr"
alias server="browser-sync start --server '_site' --files '_site'"
```

<br>

These will enable you to (for example) just type `server` into the command line instead of `browser-sync start --server '_site' --files '_site'`

The process is simliar on windows.  ([Here is a link](http://stackoverflow.com/questions/20530996/aliases-in-windows-command-prompt) explaining how to add alias' there - they are called doskeys.)

## Accounts

In addition to the github account you've already setup.  You will need an account with:

* [Airtable](http://airtable.com)
* [Slack](http://sitesforchurch.slack.com)
* [Canva](http://canva.com)

I also highly recommend you install and learn a local markdown editor on your computer.  [Typora](http://www.typora.io/) is a good one on the mac and windows platforms.


