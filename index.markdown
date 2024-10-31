---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<link rel="stylesheet" type="text/css" href="{{site.baseurl}}/assets/sidebyside.css">

<div class="homepage-container">
  <div class="image">
    <img src="{{site.baseurl}}/assets/images/nicole-in-action.jpg" alt="Nicole Jacobus speaking at an event in February 2024">
  </div>



  <div class="text">
       <h1>Nicole Jacobus</h1>

    I’m a Creative Producer and enthusiasm enthusiast based in London.<br><br>

    I primarily work as a project/production manager and producer in live events and immersive experiences, as well as for YouTube. I also perform, create prints, and communicate science - by commission and on a freelance basis.<br><br>

    Outside of work, you can find me learning aerial silks, volunteering with community organisations, or solving cryptic crosswords.<br><br>

<a href="mailto:nicole@jacobus.org">Get in touch</a> to find out more about my work or to get me involved in your projects. I'm always open to discussing new opportunities.
  </div>
</div>


<div class="index-work">
<h2 id="current-work">Current Work</h2>

{% for work in site.current-work %}
<h3>{{work.title}}</h3>
<a href="{{ site.baseurl }}{{ work.url }}">{{work.description}}</a>
{% endfor %}
</div>