---
date: 2018-11-27
title: Your Dashboard
video_id: _iH8f5alzWA
description: Have non-technical people update Jekyll sites
categories:
  - account
resources:
  - name: Source code
    link: https://github.com/CloudCannon/creative-jekyll-theme/
  - name: CloudCannon
    link: https://cloudcannon.com
type: Video
set: getting-started
set_order: 1
---

testing

## Test

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Editables

Next, we need to do is to define areas in our HTML which non-developers can update. These are called [Editable Regions](https://docs.cloudcannon.com/editing/editable-regions/) and are set by adding a class of `editable` to HTML elements.

Open `index.html` in CloudCannon and add a class of `editable` to the `h1` and `p` inside `<div class="header-content-inner">` so it becomes the following:

~~~ html
<div class="header-content-inner">
  <h1 class="editable">Your Favorite Source of Free Bootstrap Themes</h1>
  <hr>
  <p class="editable">Start Bootstrap can help you build better websites using the Bootstrap CSS framework! Just download your template and start going, no strings attached!</p>
  <a href="/about.html" class="btn btn-primary btn-xl page-scroll">Find Out More</a>
</div>
~~~