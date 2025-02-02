---
layout: default
title: Home
---

# Aarhus GAA

We are a Gaelic Football team in the heart of Denmark. Come join us for some fun, sport and socialising!

# 📝 Recent Updates

{% for post in site.posts %}

- **{{ post.date | date: "%B %d, %Y" }}** – [{{ post.title }}]({{ post.url }})

{% endfor %}

## 🔗 Links

- [Facebook](https://www.facebook.com/aarhusgaa)
- [Instagram](https://www.instagram.com/aarhusgaa)
