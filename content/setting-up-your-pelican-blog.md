Title: Setting up your Pelican blog on GitHub Pages
Date: 2016-06-18 
Category: Programming
Tags: Python, Pelican, blogging
Slug: setting-up-pelican-blog-github-pages

Step 1: Follow [this tutorial](http://mathamy.com/migrating-to-github-pages-using-pelican.html)

Step 2: Set up your git pre-commit hook by following [this tutorial](http://mavant.com/blog/2014/03/10/pelican-git-hooks-github-dot-io/)

Step 3: With this set up, you would add a new post simply by saving your post in your content folder, committing from your source directory (wherever your `pelicanconf.py` file is located), and then just pushing to origin.

Woohoo!

Basically you have two git repositories: one for your blog-source (the main Pelican directory where your `publishconf.py` file lives), and one for your output folder, which is rendered, updated and pushed to your GitHub output folder every time you push your commits from blog-source to your GitHub blog-source folder.