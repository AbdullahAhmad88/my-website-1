---
layout: default
title: Blog
---

<div style="text-align: center; margin-bottom: 30px;">
    <a href="{{ site.baseurl }}/" style="background-color: #159957; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block; border: 1px solid white;">Home</a>
    <a href="{{ site.baseurl }}/about" style="background-color: #159957; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block; border: 1px solid white;">About</a>
    <a href="{{ site.baseurl }}/blog" style="background-color: #159957; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block; border: 2px solid #fff; font-weight: bold;">Blog</a>
    <a href="{{ site.baseurl }}/contact" style="background-color: #159957; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin: 5px; display: inline-block; border: 1px solid white;">Contact</a>
</div>

# Technical Insights & Engineering Blog
**A collection of my academic research and professional journey.**

---

{% for post in site.posts %}
### [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
*Published on {{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt | strip_html | truncatewords: 30 }}

[Read Full Article]({{ site.baseurl }}{{ post.url }})

---
{% endfor %}

<footer style="margin-top: 50px; border-top: 1px solid #ddd; padding-top: 20px; text-align: center; font-weight: bold;">
    NAME: ABDULLAH AHMAD MIRZA | ROLL NO: 2025-BSCPE-131 | SECTION: A | UET FAISALABAD
</footer>
