---
title: How to host a free website with GitHub Pages (Part 1)
layout: post
date: '2021-07-18'
updated: '2021-08-03'
pin: false
tags: [web, diy, tech]
splash_img_source: "/assets/img/website.jpeg"
splash_img_caption: Website
---

### Importance of Website

A website makes it easy for people to find your company, discover what you do, and answer a bunch of questions they have on your business. By having a website people will be able to find your company when they search online. It helps create brand awareness, increases sales, improves customer experience, a media to publish updates and announcements.

Not just for businesses, a website is a powerful tool for individuals to enhance their visibility, improve personal brand, connect with people, showcase skills and talent,  share knowledge, bring more opportunities.


### Free hosting platforms

There are free website hosting providers like [blogger.com] and [wordpress]
However, the free hosting displays Ads on the website. If you are a developer, there is an alternative - Github pages.

#### Step 1: Site URL

The site URL will be in this format `https://[github user name].github.io`. If you want a different name, create a new organization with the desired name (subject to availability). Your site url will be then `https://[org name].github.io`.

#### Step 2: Create a new repository

Create a repository with the name `github username.github.io` or `orgname.github.io`

![Create GitHub repository](/assets/img/ghpages/create-rep.png)

#### Step 3: Create index.html

You can add an **index.html** file to the root of the repository to get started.

```
<html>
  <body>
    <h1>Hello from my website!</h1>
  </body>
</html>
```

#### Step 4: Set GitHub pages

Go to the repository settings and select Pages from the left menu. Select the branch and directory of website source. By default it is master branch and root directory.

![Set GitHub pages](/assets/img/ghpages/settings.png)

#### Step 5: View the page in browser

Visit the URL https://[org name].github.io to see the index.html being served as a home page.

![View page in browsers](/assets/img/ghpages/website-view.png)

You can add css files, images, js, and html files to serve a html website.

#### Next step: Creating a static website from Jekyll themes



[blogger.com]:https://www.blogger.com
[wordpress]:https://www.wordpress.com