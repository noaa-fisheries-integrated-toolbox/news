---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
sidebar:
  nav: "docs"
---

Use the search bar or sidebar options ("Posts By Year", "Posts By Tags") to find resources
about past events.

## Looking for something else?

Try the [FIT resources](https://noaa-fisheries-integrated-toolbox.github.io/resources).

## How do I get help?

[Contact the FIT team](https://noaa-fisheries-integrated-toolbox.github.io/resources/noaa%20fit/contact/).

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>