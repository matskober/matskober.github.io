---
layout: post
title: How I got here
date: '2022-08-18 18:00:02 +0200'
categories: technical blog
tags: jekyll github windows
---


Finally my Jekyll-on-Github blog is up and running. It's been a step learning curve, one could say if in need of a cliché, but I'm not sure how much I've learned, to be honest. This post is an attempt to extract some knowledge out of this digital roller-coaster experience. And also get a bit more familiar with markdown.

## The starting point

In connection with some ongoing studies/projects of mine, I was looking into ways to make a simple app based on html/css files generated from xml/xslt. The term "static website generator" seemed to tick some boxes, and of course I went down that rabbit hole, research-vice. On a low/no-budget, that tends to happen. The green fields of opensoure and ~~free-range ~~ free-of-charge software, can easily become a maze of confusing opportunities and hard choices.

And then there is Windows.

## Caught in the middle

The biggest problem I ran into when trying to grasp how to use Jekyll, was of course my lack of digital competence, paired with a tendency of mine not to make to much preparations - or do any planning at all, actually. I just sort of jumped in, following some how-to-page I ~~googled~~, sorry,  binged up - just to realize it was referring to a non-Windows computer.  But not to worry, the digital self help pages told me, if you just install this or that and get your git together... 

Retrospectively, I would assume a plan ~~would~~ could be to: 

1. Go *Microsoft Store* and install the *Ubuntu* (or *Debian*) app. This will make your Windows computer "Linux-compatible". 
2. Download and install *Ruby*, *RubyGem*, *Bundle* and *Jekyll*.
3. Log in  to [GitHub](https://github.com) find a blog-template (I used [chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)), fork this, give it at new name (your_user_name.github.io). Go to "settings/pages" and under "Build and Deploy" choose  *GitHub Actions*
4. Install [GitHub Desktop](https://desktop.github.com/)
5. Clone "your_user_name.github.io" to  a folder of your choosing on your computer using *GitHub Desktop*

At this point it should be possible, with a few edits in the *config.yml* file (e.g. the "url", pointing it to "https.//your_user_name.github.io"), to push this back and let *GitHub* do the building and deploying of the blog. After a few minutes, go back to "settings/pages". If the deployment was successful this should be reflected on "settings/pages". If something went wrong (as I assume it will), you will find  tips on how to solve it by adding *Actions*. 

Once you have been getting it up and running on "https://your_user_name.github.io", go back on your computer clone and edit the rest of the template, to make it yours. This is where the installed Jekyll comes to use. the command "jekyll serve" allows you to see your edits on localhost. When you are satisfied with the result, use *GitHub Desktop* to push the changes back to *GitHub*. 

## The end of the beginning 

Obviously I'm in no position to give technical advise, and I have no illusion that what I described above is the right way to do things. But it seems to work. For now. 


----------





<script src="https://utteranc.es/client.js"
        repo="matskober/matskober.github.io"
        issue-term="pathname"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
