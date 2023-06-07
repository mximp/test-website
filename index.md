## Welcome to my Blog!

The scope of my interests is software engineering and application security.   

## About me

I'm a Team Lead, Java developer and fan of IT technologies

My telegram channel about IT technologies: [https://t.me/itgalka_channel](https://t.me/itgalka_channel)

My Blog (this site): [https://mximp.github.io/mximp/](https://mximp.github.io/mximp/)

I'm on GitHub: [https://github.com/mximp](https://github.com/mximp)

## Posts

{% for post in site.posts %}
  {{ post.date | date: "%Y, %b %d" }}: <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  {{ post.excerpt }}
  <br/>
{% endfor %}
