---
layout: defaults/page
permalink: index.html
narrow: true
title: Yopolazi - World's Best Chili Oil
---

<div class="card mb-3">
    <img class="card-img-top" src = "/theme/img/banner.jpg/">
</div>

{% include components/intro.md %}

### Projects

John keeps himself busy on open-source and hobby projects. This is great for learning new skills. [The full list is here]({{ site.baseurl }}{% link list/projects.md %}). There's also a project page about how to [install and use this theme]({{ site.baseurl }}{% link _projects/install.md %}).


### Portfolio

John has worked in engineering for many years and has an impressive portfolio. [Browse it here.]({{ site.baseurl }}{% link list/portfolio.html %})


### Posts

John has posted a bunch of tips about how to use Friday Theme. There's the three most-recent posts below, or here's [all posts by year.]({{ site.baseurl }}{% link list/posts.html %})

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


