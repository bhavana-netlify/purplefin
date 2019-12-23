---
title: EleventyOne
subtitle: A project scaffold for getting building with Eleventy quickly.
layout: layouts/base.njk
---


## About me
Hey there, I am Bhavana aka Bana aka 2/3’s a banana (easier ?).

I am the engineer who is appreciating engineering and technology the more I surround myself with it. 10 years back I couldn’t have cared less; now I can’t get enough of it.

I am constantly discovering things that I am good at and things that I like to do. Always excited to learn new things, I will soon find the sweet spot between the two. Till then, the search continues.

When I am not in San Francisco, I am traveling the world, making up for the lack of it in the first 17 years of my life. I haven’t heard 3 sweeter words – Open Vacation Policy.

Home is where the heart is, and that is Chennai, India for me.

I currently work at PubNub, where I spend time looking for the perfect gif to send in response to anything.


## Post pages

The pages found in in the posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay }}</time>
  </li>
{%- endfor -%}
</ul>



