# HIHIHI~~~
merry christmas!!!
<p>
   &emsp;>><img src="https://github.com/yauyau566.png?size=50" height="50" width="50">
   @asj(asfa)  
</p>
<p>&emsp;&emsp;>>hahah</p>
{% for s in site.stu %}
<h>{{ s.name }}</h>
<div><span>&emsp;&emsp;</span>{{ s.content }}<div>
<div>
   &emsp;&emsp;
   {{ s.content | markdownify }}
</div>
{% endfor %}
