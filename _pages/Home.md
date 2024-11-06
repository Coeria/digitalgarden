---
layout: page
title: Home
id: home
permalink: /
---
*This is a digital garden .ೃ𓆝 𓆟 𓆞 𓆝 𓆟ೀ⋆｡🌷*


  *Specifically, this is Erica's digital garden. To learn about the specifics of what these are click [here](https://www.deemjournal.com/stories/digital-gardens)*

Basically, they are an ecological metaphor for an online notebook, which is a concept I am very excited about. My research interests and thoughts are always going to be growing and evolving, so I will make an effort to cultivate my ideas in this space.


*The digital garden template I use is free, open-source, and [available on GitHub](https://github.com/maximevaillancourt/digital-garden-jekyll-template).*

*The easiest way to make one if interested is to read this [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).*


*<strong>growing notes</strong>✎ (❁ᴗ͈ˬᴗ͈) ༉‧ ♡.✧***
{% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %} {% for note in recent_notes limit: 5 %}- {{ note.last_modified_at | date: "%Y-%m-%d" }} — [{{ note.title }}](https://github.com/maximevaillancourt/digital-garden-jekyll-template/blob/main/_pages/%7B%7B%20site.baseurl%20%7D%7D%7B%7B%20note.url%20%7D%7D)
{% endfor %}

<style> .wrapper { max-width: 46em; } </style>
