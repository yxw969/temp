
# Contributors3

{% for stu in site.stu %}
<div>
 \>\>![]({{ stu.image }})@{{ stu.user }} ({{ stu.name }})
 
   \>\>{{stu.content | markdownify}}
 </div>
{% endfor %}

Last updated: {{ site.time }}
