---
layout: post
title: "Hello world"
date: 2022-04-03 12:00 -0500
categories: general
---

Hi all. This is a first test post.

{% assign name = "ray" %}

<p>
Hello {{name}}!
</p>

{% assign cool = true %}

{% if cool %}
<p>
Yes, you are cool.
</p>
{% endif %}

{% assign cats = "Fluffy,Muffy,Duffy" | split: ',' %}
<ul>
{% for cat in cats %}
    <li>{{ cat }}</li>
{% endfor %}
</ul>