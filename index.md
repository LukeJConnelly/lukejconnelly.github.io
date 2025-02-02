---
layout: default
title: Home
---

# 📝 Recent Updates

{% for post in site.posts %}

- **{{ post.date | date: "%B %d, %Y" }}** – [{{ post.title }}]({{ post.url }})

{% endfor %}

## 🔗 Links

- [Facebook](https://www.facebook.com/aarhusgaa)
- [Instagram](https://www.instagram.com/aarhusgaa)
