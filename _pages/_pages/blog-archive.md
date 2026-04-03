---
layout: default
title: Blog
---

<div style="text-align: center; margin-bottom: 30px;">
    <a href="{{ site.baseurl }}/" style="background-color: #159957; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block;">Home</a>
    <a href="{{ site.baseurl }}/about" style="background-color: #159957; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block;">About</a>
    <a href="{{ site.baseurl }}/blog" style="background-color: #159957; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block; border: 2px solid white;">Blog</a>
    <a href="{{ site.baseurl }}/contact" style="background-color: #159957; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block;">Contact</a>
</div>

# 📝 Engineering Insights
**Exploring the intersection of Logic, Physics, and Code.**

---

{% for post in site.posts %}
<div style="background: #f9f9f9; border-left: 5px solid #159957; padding: 20px; margin-bottom: 25px; border-radius: 0 10px 10px 0; box-shadow: 2px 2px 10px rgba(0,0,0,0.05);">
  <h2 style="margin-top: 0;"><a href="{{ site.baseurl }}{{ post.url }}" style="color: #159957; text-decoration: none;">{{ post.title }}</a></h2>
  <p style="color: #666; font-style: italic;">Published on {{ post.date | date: "%B %d, %Y" }}</p>
  <p>{{ post.excerpt | strip_html | truncatewords: 35 }}</p>
  <a href="{{ site.baseurl }}{{ post.url }}" style="font-weight: bold; color: #159957;">Read Full Post →</a>
</div>
{% endfor %}

<footer style="margin-top: 50px; border-top: 1px solid #ddd; padding-top: 20px; text-align: center; font-weight: bold;">
    NAME: ABDULLAH AHMAD MIRZA | ROLL NO: 2025-BSCPE-131 | SECTION: A
</footer>
