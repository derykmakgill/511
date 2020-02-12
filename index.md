---
layout: home
title: Breaking Satoshi
---

## Read

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})<span class="date"> &raquo; {{ post.date | date_to_string }} </span>
{% endfor %}

---

## Support

If the content here is valuable to you, consider [supporting](/support) it in Bitcoin.

---


<div style="text-align: left"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button" onclick="window.location.href = 'https://breakingsatoshi.substack.com/';"></div>
