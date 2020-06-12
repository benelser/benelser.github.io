---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
title: Welcome
permalink: /welcome/
---
# This is a home page
## I get to write even more markdown here
to learn more about me take a gander [here](./about)
```powershell
Get-Awesomeness -Time $now
```

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
