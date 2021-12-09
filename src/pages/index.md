---
layout: layouts/index.tmpl.js
url: /
title: Tobias Schmidt
subtitle: Digitalisation Expert
description: Tobias Schmidt's personal website.
tags: index
---

<header>

# [{{title}}](/)

{{subtitle}}

</header>

<section>

Hi, I'm [Tobi](/profile/) a hands-on digitalisation expert in Munich. I help companies deliver reliable, personalised, and profitable digital experiences to their customers. On my blog, I am sharing thoughts on digitalisation and the web.

</section><section>

## Writing

<nav>

{% for post in search.pages("post") | reverse %}<a style="display: block;" href="{{post.data.url}}">{{ post.data.title }}</a>{% endfor %}

</nav>

</section><section>

## Connect

I am interested in meeting new people, learning new things, and helping with interesting projects. I am happy to connect on [LinkedIn](https://www.linkedin.com/in/{{author.x.social.linkedin}}) and [Github](https://github.com/{{author.x.social.github}}). To stay in touch I am looking forward to receiving an Email. If you like the content I write on my blog you can consider [subscribing](/subscribe/) to my feed.

</section><section>

## Site

My website is open-source published on [GitHub](https://github.com/{{author.x.social.github}}/{{site.x.domain}}). You can find an overview of all modules I use across the website in my [Styleguide](/styleguide/). Check out my [Colophon](/about/) to learn how I created this site. In the [Privacy Policy](/privacy/), you will find information on how this website handles your data. The [Legal Notice](/legal/) includes other important information.

</section>

{% include "abbr.njk" %}
{% include "links.njk" %}