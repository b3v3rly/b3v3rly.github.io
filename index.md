---
layout: default
title: Home
---

# 🌸 Welcome to Bev's Cybersecurity Blog

Hi! I'm Bev, a cybersecurity student passionate about:

- 🔐 Cybersecurity
- 🌐 Networking
- 🚩 CTF Competitions

## 📚 What You'll Find Here

- CTF Writeups
- Study Notes
- University Projects

## ✨ Latest Writeups

{% raw %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
{% endraw %}

Stay tuned for upcoming challenge writeups and learning notes.
