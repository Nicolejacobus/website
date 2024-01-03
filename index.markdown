---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Nicole Jacobus


I'm a Creative Producer and enthusiasm enthusiast based in London. 

My current work projects are as a Production Manager for <a href="https://entourage.live/" target="_blank">Entourage</a>, Producer for <a href="https://www.youtube.com/@standupmaths" target="_blank">Stand Up Maths</a>, Project Manager for the <a href="https://immersiveexperience.network/" target="_blank">Immersive Experience Network</a> and Science in Schools Presenter for the <a href="https://www.rigb.org/learning/science-shows-your-school" target="_blank">Royal Institution</a>.

I also perform, produce prints, stage manage and communicate science by commission and on a freelance basis.

<a href="mailto:hinicole@jacobus.org">Get in touch</a> to find out more about my work or get me involved in your projects. I'm always open to discussing new opportunities.

<div class="index-jobs">
<h2 id="jobs">Current Projects</h2>

{% for job in site.jobs %}
<h3>{{job.title}}</h3>
<a href="{{ site.baseurl }}{{ job.url }}">{{job.description}}</a>
{% endfor %}
</div>