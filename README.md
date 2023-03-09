# How to host an online resume and README

## Purpose

The purpose of this README is to help you format a resume by using GitHub Pages.

## Prerequisites

Firstly, before continuing, we will need the following things installed, you will need Git, Ruby, and a Markdown editor such as Visual Studio.   Once we have completed all the necessary prerequisites we can now start following the instructions on how to host your resume on a static site.

## Instructions

### Creating a GitHub Pages site with Jekyll

#### Create a repository for your site



We will assume this is your first time making a repository so we will go step by step.

1. Go on the GitHub Pages site and sign in or create an account.
2. In the top-right corner of the page you should see a drop-down menu with a + symbol, click it and select New repository.
3. For the repository name type in <user>.github.io, and all uppercase letters in the name must be in lowercase.
4. Select the repository visibility you desire, each option has a small description that describes what it does.

### Testing your new site locally

#### How to install Jekyll




#### Building your site locally

1) Open Git Bash.
2) Go to the publishing source for your site within Git Bash.
3) Run ``` bundle install ```.
4) Run your Jekyll site locally by typing in
``` bundle exec jekyll serve ```.
5) You will then see a line that looks like ``` Server address:http://localhost:4000 ```, you can copy that link and go to your website.


### Add a theme to your GitHub Page with Jekyll

We will be using a Jekyll theme hosted on GitHub in this tutorial.

1) Go on GitHub Pages.
2) Select the repository.
3) Within the repository, select the ```_config.yml``` file.
4) In the top right corner, you should see a pencil icon to open the file editor, click it.
5) Somewhere in the file add a new line and type ```remote_theme: THEME-NAME```, where theme THEME-NAME is the name of a theme you want.
6) Then scroll to the bottom and commit to the changes.


## Acknowledgements: 
I would like to acknowledge Andrew Etter for his book Modern Technical writing. In addition to that I would like to also acknowledge my group mates  Craig and Xu for peer reviewing my README.

### FAQs

**Q: Why should I build my site locally?**

A: You should build it locally because you can then test your site locally and it will update right away. Sometimes if you use a host like GitHub the servers can be down or take a long time to push the updates you just made. So overall it is just for convenience.













