---
title: How to host a website for free with GitHub Pages
layout: post
date: '2021-07-18'
updated: '2021-08-03'
pin: false
tags:
- web
- diy
- tech
splash_img_source: https://ucarecdn.com/02e3baf2-211c-48a1-96d7-dd2126fc4e8a/-/preview/-/quality/smart/-/format/auto/
splash_img_caption: Website
---

### Importance of Website

A website makes it easy for people to find your company, discover what you do, and answers a bunch of questions they have on your business. It helps create brand awareness, increases sales, improves customer experience, serves as a media to publish updates and announcements.

Not just for businesses, a website is a powerful tool for individuals to enhance their visibility, create a personal brand, connect with people, showcase skills and talent,  share knowledge, bring  opportunities.

### Free hosting platforms

 [Blogger](https://www.blogger.com){:target="_blank"} and [Wordpress](https://www.wordpress.com){:target="_blank"} provide free hosting options. 
However, they display Ads on the website. It is user friendly to create and manage content but it comes with a cost of some performance delays.  If you are tech savvy or a developer, there is Github pages.

### GitHub Pages
#### Step 1: Site URL

The site URL will be in this format `https://[github-username].github.io`. If you want a different name, create a new organization with the desired name (subject to availability). Your site url will be then `https://[orgname].github.io`.

#### Step 2: Create a new repository

Create a repository with the name `github-username.github.io` or `orgname.github.io`

![Create GitHub repository](/assets/img/ghpages/create-rep.png)

#### Step 3: Create index.html

You can add an **index.html** file to the root of the repository to get started.

```html
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
