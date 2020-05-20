
# Contributors3

{% for stu in site.stu %}
<div>
 <span>&gt;&gt;<img src="{{ stu.image }}" >@{{ stu.user }} ({{ stu.name }})</span>
 
 <div>&nbsp&nbsp&nbsp&gt;&gt;{{stu.content | markdownify}}</div>
 </div>
{% endfor %}

Last updated: {{ site.time }}
