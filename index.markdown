---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Nicole Jacobus

Add text here using **Markdown**. Use asterisks for italics, etc (google it)

*Text intro, some photos, summary of what I do and
where I learned to do it*

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.



<a href="{{site.email}}">Get in touch!</a>

<div class="index-jobs">
<h2 id="jobs">Jobs</h2>

{% for job in site.jobs %}
<h3>{{job.title}}</h3>
<a href="{{ site.baseurl }}{{ job.url }}">{{job.description}}</a>
{% endfor %}
</div>