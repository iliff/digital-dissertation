---
layout: default
---

### Description of Project

Here, you can give a brief outline of the project or even just post your abstract from proposal.

### Participants (Commitee Members)

List any additional participants in the project and link to their social or professional profiles here.

### Link to Zotero for bibliography

See [Shawn Goodwin's](https://github.com/e2dubba) proof of concept for [rendering a Zotero library in GitHub pages](https://github.com/e2dubba/e2dubba.github.io/blob/master/bibliography.html).


### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>