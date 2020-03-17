---
layout: post
title: "2. Uploading completed web page to GitHub"
date: 2016-11-07
---

We will upload this files to Github to freely host in there. GitHub gives chance to host all kind of public files under a page such as [mehmetakifakkus.github.io](http://mehmetakifakkus.github.io), means **username.github.io**. 

This is called [Github Pages](https://pages.github.com/) which is a free service by GitHub. GitHub has Jekyll system in it and serves your files with this manner. What we will do is a simple process:

- create a GitHub project with the name: username.github.io
- in your desktop create a git repository and upload your files with these codes:

{% highlight bash linenos %}
  git init
  git add *
  git remote add origin https://github.com/username/username.github.io.git
  git push -u origin master
{% endhighlight %}

- done!
