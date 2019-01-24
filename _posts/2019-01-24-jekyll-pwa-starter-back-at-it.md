---
title: Jekyll PWA Starter - Back at it
date: '2019-01-24 10:55am'
layout: posts
categories: blog
abstract: Getting back to Jekyll PWA Starter for 2019
author: Josh Vogt
permalink: '/posts/:categories/:title/'
---
I've not touched the [Jekyll PWA Starter](https://github.com/dumaurier/pwa_jekyll) in a while but I'm starting it back up. First thing is the creation of a clean branch to start from. If you clone the master branch you end up with a whole bunch of content that you don't want or need so you can now clone a clean branch that has most of cruft removed. 

**Clean Branch:**

To clone the clean branch run the following command in you Terminal:

```
git clone -b clean --single-branch https://github.com/dumaurier/pwa_jekyll.git
```

This still has a few example posts for each post type but it's easier to get rid of them and start with your own stuff.

## Next Steps:

I'm going to add a few things to the starter over the next week or so. An incomplete list (meaning the things that I remember I want to add) are:

* Option in the \`data/about.yml\` file to toggle on/off Web Mentions
* 'Deploy with Netlify' button as described here: <https://www.netlify.com/docs/deploy-button/>
* Add option to use Bootstrap for anyone that doesn't want to bother writing their own CSS
* Streamline process to add IndieWeb microformats and WebMentions integration



I should note, tangentially, that I keep playing with other Jekyll-esque static site generators and none of them are as much fun to use as Jekyll. Though I will concede that [Next.js](https://nextjs.org/) is quite lovely.
