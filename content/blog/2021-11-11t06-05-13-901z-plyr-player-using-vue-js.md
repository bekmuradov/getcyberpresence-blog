---
createdAt: 2021-11-11T06:05:13.901Z
title: Plyr Player using Vue JS
description: In this guide we will build custom plyr player using Vue 3.
---
![hand in the water](https://source.unsplash.com/1600x900/?nature,water)

VueBlogger is a light-weight blogging site generator for Vue.js, built for geeks who wanted to write their blog site in Vue and write posts in Markdown.

I developed it for a reason: there isn't really a simple blogging tool for Vue. VuePress works, but it's to complicated. So for that purpose, I developed this light-weight blogging site for Vue: VueBlogger.

You can host it on any server that has Nodejs and Vue installed. Actually, you even don't need them if you already built your blog on your own laptop: just host the HTML and JavaScript files directly!

```json
{
    "config": {
        "username": "Your username",
        "avatarPath": "Your avatar image url",
        "description": "Your blog description",
        "name": "Your name",
        "blogTitle": "Your blog title",
        "blogStartYear": 2019  // The year your blog started. Used to generate the copyrights in the footer.
    },
    "contacts": [
        {
            "name": "Contact method",
            "value": "Contact information, such as your email address",
            "link": "Contact link, such as `mailto:email@example.com`"
        }
    ]
}
```