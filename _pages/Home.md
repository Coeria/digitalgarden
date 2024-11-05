---
layout: page
title: Home
id: home
permalink: /
---
*this is a ==digital== garden .ೃ𓆝 𓆟 𓆞 𓆝 𓆟ೀ⋆｡🌷*


  *Specifically, this is Erica's digital garden. To learn more about what these are click [here](https://www.deemjournal.com/stories/digital-gardens)*

*The digital garden template I use is free, open-source, and [available on GitHub here](https://github.com/maximevaillancourt/digital-garden-jekyll-template).*

*The easiest way to get started is to read this [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).*

*<strong>growing notes</strong>✎ (❁ᴗ͈ˬᴗ͈) ༉‧ ♡*.✧*
*<ul>*
  *{% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}*
  *{% for note in recent_notes limit: 5 %}*
    *<li>*
      *{{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>*
    *</li>*
  *{% endfor %}*
*</ul>*

*<style>*
  *.wrapper {*
    *max-width: 46em;*
  *}*
*</style>*
