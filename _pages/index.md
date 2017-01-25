---
layout: home
title: Hello
permalink: /
---
I'm Matthew Graybosch, a science fantasy author, self-taught developer, and long-haired metalhead from New York. You can [learn more about me here](/about/) or [see what I'm up to now](/now/).

## Recent Posts

Here are my latest blog posts. You might find something you like.

<ul>
{% for post in site.posts limit: 10 %}
  <li><span class="post_date">{{ post.date | date: "%b %d, %Y" }}</span> &mdash; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

You can find all of my posts [in the archive](/blog/).

## Where to Find Me

I'm active on a number of social media sites, primarily Reddit and Google+. I also share links to blog posts on Twitter, and syndicate my posts on Google+, Medium, and Facebook.