# How to host an online resume

## Purpose

The purpose of this README is to help you set up a static site which then you can host a resume on with GitHub Pages.

![Gif of resume](https://recordit.co/nHJjAd5tkH)

## Prerequisites

Firstly, before continuing, we will need the following things installed, you will need Git, Jekyll, Ruby, and a Markdown editor such as Visual Studio or Ghostwriter.   Once we have completed all the necessary prerequisites we can now start following the instructions on how to host your resume on a static site.

How to install [Ruby](https://www.ruby-lang.org/en/documentation/installation/)

How to install [Jekyll](https://jekyllrb.com/docs/installation/)
## Instructions

### Create a repository for your site

In Etters book Modern Technical Writing he mentions how you can host a static website basically anywhere but we have decided to run our demo with GitHub Pages because it's the most popular and accessible option.

We will assume this is your first time making a repository so we will go step by step.

1. Go on the GitHub Pages site and sign in or create an account.
2. In the top-right corner of the page you should see a drop-down menu with a + symbol, click it and select New repository.
3. For the repository name type in <user>.github.io, and all uppercase letters in the name must be in lowercase.
4. Select the repository visibility you desire, each option has a small description that describes what it does.

### Building your site locally

Etter mentions how he loves static websites because you can host them anywhere, without needing a database and you can test them on your computer without needing to install external processes. In his book he mentions a list of sites to host your page, but for my tutorial we will be using GitHub Pages to help host our page.

1) Open Git Bash.
2) Go to the publishing source for your site within Git Bash.
3) Run the command ``` bundle install ```. 
4) Run your Jekyll site locally by typing in
``` bundle exec jekyll serve ```. 
5) If done successfully you should see a lot of text start popping up in the window. Then search for a line of text that looks like ``` Server address:http://localhost:4000 ```, you can copy that link and go to your website.


### Add a theme to your GitHub Page with Jekyll

Etter has mentioned when picking a theme you should pick something that is accessible and clean, but this is also a time to help stand out from the pack and be noticed.

We will be using a Jekyll theme hosted on GitHub in this tutorial.

1) Go on GitHub Pages.
2) Select the repository.
3) Within the repository, select the ```_config.yml``` file.
4) In the top right corner, you should see a pencil icon to open the file editor, click it.
5) Somewhere in the file add a new line and type ```remote_theme: THEME-NAME```, where theme THEME-NAME is the name of a theme you want.
	- Here is a link to a list of [supported themes](https://pages.github.com/themes/) on GitHub Pages.
6) Then scroll to the bottom and commit to the changes.
7) Check your resume page again to see if the theme has been applied.

## More Resources

Some more resources that can help you complete this tutorial.

[Markdown tutorial](https://www.markdowntutorial.com/)

[Etter's Book](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

[List of Markdown editors](https://www.oberlo.ca/blog/markdown-editors)

## Acknowledgements

I would like to acknowledge Andrew Etter for his book Modern Technical writing. In addition to that I would like to also acknowledge my group mates  Craig and Xu, for helping me with some of the technical aspects of how to host the resume in the first place. Without them I wouldn't have been able to even write this tutorial.

### FAQs

**Q: Why should I build my site locally?**

A: You should build it locally because you can then test your site locally and it will update right away. Sometimes if you use a host like GitHub the servers can be down or take a long time to push the updates you just made. So overall it is just for convenience.

**Q: How can I use a use a theme that isn't hosted on GitHub already?**

A: To host a theme other than a Jekyll theme hosted on GitHub, you should still follow steps 1-4 on the instructions about "Add a theme to your GitHub Page with Jekyll". After you have completed those steps now you can follow these alternative instructions.

1) Anywhere in the file type ```theme: THEME-NAME```
	- Replace the THEME-NAME with the name of the theme in your README
2) Confirm your changes and that's it.














