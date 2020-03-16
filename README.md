# Rails Girls Demo Project

## Introduction
This is a demo project for guiding learners on the basics of the Ruby on Rails framework. The step by step instructions are available [here](https://guides.railsgirls.com/app) on the Rails Guides website.

Having been a coach for Rails Girls events several times, I realised that it's very rare to complete this project with the learners in a single day. The main reasons for this are:

- Most learners use PCs which require set up for development. This usually takes time as the process is not as smooth as it would be on unix platforms.
- Some learners may not at all be familiar with programming. So as a coach, you have to take time to introduce programming concepts using Ruby, before starting to build the project. This can be overwhelming to the learners and usually takes up almost half the session.

With this mind, I hope that this repo acts as a point of reference. As a coach, you can point your learners to this repo as an example of what the completed project looks like. For learners, use this as a base if you want to continue building the app.

## Installation
### Requirements
- Ruby 2.6.5
- Rails 6.0.2

To install these on your platform, refer to the [Rails Girls guide](https://guides.railsgirls.com/install). You'll also find instructions on how to install other requirements like text editors in case you don't have them.

### Clone the repo
You will need [Git](https://git-scm.com/) on your machine to clone this repo. Download and install the relevant version for your platform.

The simplest way to clone the repo is by using HTTPS. You will need to enter your Github credentials.
```
git clone https://github.com/bmwenda/railsgirls.git
```

If you have set up ssh keys on Github, you can clone using ssh
```
git clone git@github.com:bmwenda/railsgirls.git
```

To learn more about this, visit the [Github help page](https://help.github.com/en/github/using-git/which-remote-url-should-i-use) about this topic.

## Development
### Bundle
After cloning, cd to the `railsgirls` folder.
```
cd railsgirls
```

 Run `bundle install` to install dependencies.

### Start server
Run `rails server` or just `rails s` to start the app server on your machine. Visit the url `localhost:3000` or `127.0.0.1:3000` to view the application on your browser.

### Customize
If you want to do your own practise and get your feet dirty, you'll need to [fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) this project.

You will need to learn some basic git commands so that you can `push` the changes you make to your repo. Refer to the [git-handbook](https://guides.github.com/introduction/git-handbook/) by Github for a quick introduction to git.
