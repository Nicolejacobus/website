---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Nicole Jacobus


I’m a Creative Producer and enthusiasm enthusiast based in London.

I primarily work as a project/production manager and producer in live events and immersive experiences, as well as for YouTube channels. I also perform, produce prints, and communicate science by commission and on a freelance basis.

Outside of work, you can find me training aerial silks, volunteering with Jewish community organisations, or teaching myself the accordion.

<a href="mailto:hinicole@jacobus.org">Get in touch</a> to find out more about my work or get me involved in your projects. I'm always open to discussing new opportunities.

<div class="index-work">
<h2 id="current-work">Current Work</h2>

{% for current-work in site.work %}
<h3>{{current-work.title}}</h3>
<a href="{{ site.baseurl }}{{ work.url }}">{{work.description}}</a>
{% endfor %}
</div>