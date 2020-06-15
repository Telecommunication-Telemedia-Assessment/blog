# avt's blog
AVT's static web blog hosted on github pages.
Access it via: [https://telecommunication-telemedia-assessment.github.io/blog](https://telecommunication-telemedia-assessment.github.io/blog)

## adding posts

Simply use the provided template `_posts/template.md` and follow the following steps:

* rename the file to a dateform with some title: 2020-06-16-my-mighty-post.md , the format is `YYYY-MM-DD-title.md`
* change the template according to your post:

```md
---
layout: post
title:  <TITLE>
categories: blog
author: <AUTHOR>
---
this line is shown on main page.

the following lines not. but they are shown inside the post.


```

Important here is, `<TITLE>` is the title shown on the main page, `<AUTHOR>` should be unified across all posts, usually `<FIRSTNAME> <LASTNAME>`.

The first post lines are also the "preview" on the main page.





## development
The overall blog is based on [jekyll](https://jekyllrb.com/)-- that is a static web page hosting software based on ruby, and uses the [minima template](https://github.com/jekyll/minima/tree/2.5-stable) (version 2.5).

All custumizations are based on the given template, be carefully if you want to change something, for local preview and development setup ruby and run more or less the `./preview.sh` script.
