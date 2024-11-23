---
layout: post
title:  "Building my personal site with Jekyll"
date:   2024-11-20 11:00:00 +0200
categories: web development
---
Describing my process on creating this site.


I realised that I was in a need for personal web-page that includes my CV, projects and a blog.

After some research I decided to go with GitHub Pages and using Jekyll for the site development. 



### GitHub Pages
GitHub offers free hosting for your website directly from a repository. There is a CI/CD pipeline so creating and managing the site is easy as all you need to do is push changes into the branch that is the publishing source.

For more info visit the official [GitHub Pages site.](https://pages.github.com/)

### Why Jekyll?
Jekyll is a static-site generator and does not require any backend work such as databases. Site contents, namely posts and pages can be written in markdown and the markdown is parsed into HTML when publishing. This makes it
a breeze to publish new posts.


> Jekyll is used for 'Simple, blog-aware, static sites'.


### Development
I decide to start with Jekyll's default theme minima, as there is not a lot of features in it and serves as a good starting point.

>"A product is well engineered when there is not a feature to be removed anymore"

As I don't have any earlier experience in web-development it is better to study how the default theme is constructed and add files that overwrite the theme files as needed. This way it is easier to follow design practices that are implemented in the original theme and learn from more experienced programmers the 'right way'.

To provide some context, I have been working with Python and SQL, and a little bit with C#. While starting this project I have only shallow knowledge on version control systems such as Git, but expect to become more knowledgeable after a while of developing.

If the project starts to go out of hand I may later publish it as a template for others to use. The main goal is to keep the site light and responsive while adding a few nice touches.