---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
 <h1>Nicole Jacobus</h1>

<link rel="stylesheet" type="text/css" href="{{site.baseurl}}/assets/sidebyside.css">

<div class="container">
  <div class="image">
    <img src="{{site.baseurl}}/assets/images/headshot.jpg" alt="Nicole Jacobus">
  </div>

  <div class="text">
      

    I’m a Creative Producer and enthusiasm enthusiast based in London.<br><br>

    I primarily work as a project/production manager and producer in live events and immersive experiences, as well as for YouTube. I also perform, create prints, and communicate science - by commission and on a freelance basis.<br><br>

    Outside of work, you can find me training aerial silks, volunteering with community organisations, or teaching myself the accordion.<br><br>

<a href="mailto:hinicole@jacobus.org">Get in touch</a> to find out more about my work or get me involved in your projects. I'm always open to discussing new opportunities.
  </div>
</div>


<div class="index-work">
<h2 id="current-work">Current Work</h2>

{% for work in site.current-work %}
<h3>{{work.title}}</h3>
<a href="{{ site.baseurl }}{{ work.url }}">{{work.description}}</a>
{% endfor %}
</div>