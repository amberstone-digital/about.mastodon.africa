---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: home
---

Welcome! You're behind the scenes of mastodon.africa right now - on this site, you'll find more information about:

<ul>
  <li>Our mission and vision for mastodon.africa</li>
  <li>Our code of conduct</li>
  <li>The standard Terms and Conditions</li>
  <li>protocol7 - the company providing this service</li>
</ul>

If you have any questions or concerns not covered here, you can contact the administrator directly at: <a href='&#109;ailto&#58;%77o&#37;67an%4&#48;prot%6&#70;%63%6F%6C7&#46;co&#46;&#122;&#97;'>wogan&#64;pro&#116;&#111;col7&#46;co&#46;z&#97;</a>. Please allow 2-3 business days for a response.

<hr>

{% for post in site.posts limit:1 %}
<h4>Latest Update: <strong>{{ post.date | date: "%d %B %Y" }}</strong></h4>
<h3>{{ post.title }}</h3>
<div>{{ post.excerpt }}</div>
<a href="{{ post.url }}">Read more &raquo;</a>
{% endfor %}
