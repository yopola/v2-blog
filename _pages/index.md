---
layout: defaults/page
permalink: index.html
narrow: true
title: Yopolazi&reg; - World's Best Chili Oil
---

{% include components/claim.html %}

<div class="card mb-3">
    <img class="card-img-top" src = "/theme/img/banner.jpg">
</div>

{% include components/intro.md %}

<hr>
## A Spicy Tradition Since 1735

Yopolazi (Also known for Youpolazi) is a traditional chili oil from Xi'an, the old capital of China, the home of Terra Cotta Warrior and the starting point of the ancient Silk Road. The spices which were used in the creation of Yopolazi sauce were originally derived via Europe and the Silk Road around 1500-1600 A.D. In 1735, and the oldest recorded chili recipe was found in 'The General History of Shaanxi' as compiled by Emperor Yongzheng, the fifth emperor of the Qing dynasty. This recipe serves as the basis for the Yopolazi.

<hr>
## What's Inside Yopolazi&reg;
<p>
	- Vegetable Oil (California)<br>
	- Chili Pepper (California)<br>
	- Pepper Corn (Sichuan)<br>
	- White Pepper (Southeast Asia)<br>
	- Seasame (India)<br>
	- Salt (California)<br>
	- Other Spices Mix (Sichuan, Southeast Asia, South America)<br>

</p>

<hr>
## How To Use

You can use it for any food, and we have a recommended list below:
{% include components/usage.html %}
You can [find more recipes]({{ site.baseurl }}{% link list/portfolio.html %}) with yopolazi in our recipes page.


<hr>
## Featuring Recipes

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


