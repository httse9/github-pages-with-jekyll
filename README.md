# HIHIHIHI
merry christmas

{% for s in site.stu %}
<h>{{ s.name }}</h>
<p>{{ s.content | markdownify }}</p>
{% endfor %}
