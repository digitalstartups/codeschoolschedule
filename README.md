# DS Open Code School - JavaScript Schedule

#### **Disclaimer: Read Install Docs for any software installed here** ####
Based on technologies identified in:
  [HackReactor Prep Course](https://www.hackreactor.com/prep-programs/)
  
  [Front End Developer Handbook 2017 - Frontend Masters](https://frontendmasters.gitbooks.io/front-end-handbook-2017/content/2017.html)
  
  [Nodeschool](https://nodeschool.io/)
  
  [Khan Academy](https://www.khanacademy.org)
  

# Basic I (Setup and web-dev basics)
This schedule is grossly biased toward *nix operating systems: This means you need a Mac with OSX or an old laptop installed with a (preferably new) Debian/Ubuntu Linux distribution.

## Environment setup
<img src="http://i.imgur.com/g9LiMF9.jpg" width="640">
We need to install development tools and editors. We don't know which editor will suit a person so let's keep options open.

*SWBAT: install packages, upgrade the terminal, show basic familiarity with editors, (optional:see accelerated development with vi/vim*)
- install Terminator (Linux) or [iTerm2](https://www.iterm2.com/downloads.html)(OSX) (A better terminal experience)
- install [brew](http://brew.sh/)(OSX)/[aptitude](http://askubuntu.com/questions/311130/what-does-sudo-apt-get-install-aptitude-do)(Linux)
- Linux: 
    sudo apt-get update 
- or OSX: 
    xcode-select --install
    brew doctor
    
- install [VS Code](https://code.visualstudio.com/) (optional: with vim plugins) (#TODO why)

(Optional)
- install / update vim [OSX help](http://www.prioritized.net/blog/upgrading-vim-on-os-x/)

- install Atom with vim
- watch **[Vim: Precision editing at the speed of thought](https://vimeo.com/53144573)**


Tip:
- Linux: sudo apt-get install <package name>
- brew install <package name>


We're going to use Javascript so let's update/install node:

*SWBAT: Install / upgrade the system node from nodejs.org, know where to get node.js from*
- install [node](https://nodejs.org/en/download/)

We will use nvm to manage node versions we may need:

*SWBAT: Install nvm, change node version*
- install [nvm](https://github.com/creationix/nvm)

We may need yarn, an alternative node package manager:

*SWBAT: Install yarn, show familiarity with yarn*
- install [yarn](https://yarnpkg.com/) --without-node


## [How the internet works (infographic)](http://visual.ly/how-internet-works)
<img src="https://i.imgur.com/xvE6YHS.jpg" width="640">

*SWBAT: Get a broad perspective of how the internet works, how web applications work*
- Networks
- Servers
- Clients (Web, News, Email)

## Tools, Security, Version Control
Controlling versions of code (versioning) can be difficult, especially when there is more than one person in a team, and more so when the team is distributed. Distributed Version Control Systems (DVCS) help to organise code and store it in the cloud for collaboration, security, and accessibility

### Install the tools
*SWBAT: Install version control tools, have an account on popular version control sites, understand the purpose of Markdown*
- install [hg](https://mercurial.selenic.com/wiki/Download) & [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- GitHub / Bitbucket (and DVCS)
- Discuss Markdown (mentored session)
- [Learn about Markdown](http://markdowntutorial.com/) - nodeschool

### Key pairs and authentication
*SWBAT: Understand security keys and key pairs*
- Key pairs theory (mentored session)
- [Public-key Cryptography - Wikipedia](https://en.wikipedia.org/wiki/Public-key_cryptography)
- [Generating SSH Keys - github](https://help.github.com/articles/generating-ssh-keys/)
- [Nodeschool.io - git-it](https://github.com/jlord/git-it-electron)
- Reference: [Git Book](https://git-scm.com/book/en/v2)
- [Joel Spolsky's Mercurial Tutorial](http://hginit.com/) (optional)

### Vim, Slack, & Tool practice
*SWBAT: Become familiar with vi/vim (optional), know how to communicate with different teams in Slack*
- [shortcutfoo](https://www.shortcutfoo.com/) Vim units 1 & 2 (free - for now) (optional)
- watch/read/learn more **[vimcasts.org](http://vimcasts.org/)**
- For later on: [vimgolf](https://github.com/igrigorik/vimgolf) or [vimgolf site](vimgolf.com) (optional)
- a vim game: [Vim Adventures](http://vim-adventures.com/) (optional)
- Learn/Install [Slack](https://slack.com/) - for team communication
- Tooling practice philosophy - why practice? (mentored session)


## Learning HTML/CSS/JQuery
*SWBAT: HTML syntax and usage, HTML structures, Markdown, CSS syntax and purpose, JQuery basics (for manipulating HTML/CSS elements)*
- [Nodeschool: LearnYouHTML](https://github.com/denysdovhan/learnyouhtml)
- [Khan Academy HTML/CSS](https://www.khanacademy.org/computing/computer-programming/html-css)
- Optional: [Ryans Tutorials: HTML Tutorial](http://ryanstutorials.net/html-tutorial/)
- Optional: [Ryans Tutorials: CSS Tutorial](http://ryanstutorials.net/css-tutorial/)
- [Nodeschool: How to Markdown](https://github.com/workshopper/how-to-markdown)
- [JQuery - Codecademy](https://www.codecademy.com/tracks/jquery) (3 hours)


## Learning the command line
*SWBAT: Navigate around the command line, be familiar with basic command line tools*
- [Learn the command line - Codecademy](https://www.codecademy.com/en/courses/learn-the-command-line/) (3 hours)
- Optional: [Ryans Tutorials: Linux Tutorial](http://ryanstutorials.net/linuxtutorial/)
- Make code folder $HOME/code
- Make Nodeschool folder $HOME/code/nodeschool


# Basic II (Basic JavaScript and tooling)
<img src="http://i.imgur.com/6aclmM6.png" width="640">
*This section is about learning the basics of JavaScript and simple programming*

## Basic JavaScript
*SWBAT: Understand basic JavaScript syntax, understand basic JavaScript data structures, read/write code with regards to scope*
- [Nodeschool.io - javascripting](https://github.com/sethvincent/javascripting)
- [Mutating vs non-mutating array methods](http://lorenstewart.me/2017/01/22/javascript-array-methods-mutating-vs-non-mutating/) (worth reviewing when you get to the "Looping through arrays" lesson)
- [Nodeschool.io - scope-chains-closures](https://github.com/jesstelford/scope-chains-closures)




# Intermediate I
*More Javascript proficiency, plus Regex, packages (NPM), ES6/7 language knowledge*

## Regex
*SWBAT: Understand what a REGEX is and what it is for. Have practice and deciphering REGEXs*

Regular Expressions (Regex) are used to 'pattern-match' strings, urls, data, and more. They are simple and effective, and usually fast to use

- [Ryan's Tutorials: Regex Basics](http://ryanstutorials.net/regular-expressions-tutorial/regular-expressions-basics.php)
- Play [Regex Crossword!](https://regexcrossword.com/) (optional)

## node.js
*SWBAT: Set up a simple node web server*
Node.js is the Server-side part of JavaScript that facilitates development build tools and other command line software, and servers.
- [Nodeschool.io - learnyounode](https://github.com/workshopper/learnyounode)

## NPM
*SWBAT: Set up a simple node web server*
NPM is a tool for downloading JS packages/libraries from the NPM site.
- [Nodeschool.io - how-to-npm](https://github.com/npm/how-to-npm)

## JavaScript: ES6 and more
- [Nodeschool.io - count-to-6](https://github.com/domenic/count-to-6)

## Optional Extras: Streams and Regex
*SWBAT: Use REGEX, use node streams for piping information, make a desktop electron app*
[Nodeschool.io - regex-adventure](https://github.com/substack/regex-adventure)
[Nodeschool.io - stream-adventure](https://github.com/substack/stream-adventure)
[Nodeschool.io - elementary-electron](https://github.com/maxogden/elementary-electron)



# Intermediate II
*More Intermediate JavaScript*

### Server frameworks, SASS, and precompilers
At this stage it's important to have got a handle on the Command Line and how HTML and CSS work before moving on
DevOps - Ubuntu with ?

- - tentative: [Nodeschool.io - lololodash](https://github.com/mdunisch/lololodash)
- - tentative: [Nodeschool.io - planetproto](https://github.com/sporto/planetproto)
- [Nodeschool.io - makemehapi](https://github.com/hapijs/makemehapi)
- [Nodeschool.io - promise-it-wont-hurt](https://github.com/stevekane/promise-it-wont-hurt)
- [Nodeschool.io - learn-sass](https://github.com/claudiopro/learn-sass)
- [Nodeschool.io - bug-clinic](https://github.com/othiym23/bug-clinic)
- - tentative: [Nodeschool.io - test-anything](https://github.com/finnp/test-anything)
- [Nodeschool.io - levelmeup](https://github.com/workshopper/levelmeup)
- [Nodeschool.io - browserify-adventure](https://github.com/substack/browserify-adventure)
- Optional Extra [Nodeschool.io - expressworks](https://github.com/azat-co/expressworks)

# Advanced I
- [Nodeschool.io - functional-javascript-workshop](https://github.com/timoxley/functional-javascript-workshop)
- [Nodeschool.io - async-you](https://github.com/bulkan/async-you)
- [Nodeschool.io - learnyoumongo](https://github.com/evanlucas/learnyoumongo)
- [Nodeschool.io - tower-of-babel](https://github.com/yosuke-furukawa/tower-of-babel)

# Advanced II

- [Nodeschool.io - learn-generators](https://github.com/isRuslan/learn-generators)
- [Nodeschool.io - esnext-generation](https://github.com/jesstelford/esnext-generation)
- [Nodeschool.io - learnyoureact](https://github.com/tako-black/learnyoureact)
- [Nodeschool.io - learnyoucouchdb](https://github.com/robertkowalski/learnyoucouchdb)
- [React Enlightenment Gitbook](https://www.reactenlightenment.com/)

TODO ES6 intro:
 https://github.com/kentcdodds/es6-workshop
 checkout https://github.com/jesstelford/esnext-generation
 checkout https://github.com/yosuke-furukawa/tower-of-babel
 where does this fit: https://github.com/kohei-takata/learnyoureact
 

- Twitter Bootstrap tutorial (advanced HTML/CSS) [Tutorial Republic](http://www.tutorialrepublic.com/twitter-bootstrap-tutorial/)


Notes:

Machine setup
Editors: VS Code, Atom, Code Pen, Vim

Basic JS

Recursion - Advanced looping algorithms

Higher Order Functions - Currying and functional programming

HTML, CSS, JQuery - Basic web development, nodeschool, codeacademy

Github - DVCS (distributed version control systems)

Linux Cmd Line - server navigation/administration


Engineering Craftsmanship - Thinking right

Good clean code - how and why, style guides/coding styles

Technical communication - ?

Empathetic communication in teams - ?

Data Structures - designing and handling data

JS Instantiation patterns - ?

JS:
ES5, ES6, Asynchronous Code, Promises

Client Side:
MVC, AJAX, Frameworks, Tools

Server Side:
node.js, npm, express.js, authentication


Deployment:
Heroku
Digital Ocean, EC2
Serverless

Databases and storage concepts:
SQL
MongoDB
ORMs
Redis

## PROJECTS
Basic Apps:
project?

Legacy code:
?

New Languages:
Go? Python? Elm?


New Technologies - ?

Testing - ? TDD, 

Continuous Development - faster feedback, faster development, more focus, higher quality code, more engagement


TEAMS:
Agile - vs waterfall?

Iterative development

Advanced git techniques - ?


Job Prep:
study plan, daily schedule

Job materials:
CV, Cover letter, Social (Li, AngelList)

Applications/Companies:
Company Culture - an emergent property

App life cycle

Opportunities

Portfolio??

*SWBAT: *
