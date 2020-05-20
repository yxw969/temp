
# Contributors3

{% for stu in site.stu %}
<div>
 <span>&gt;&gt;<img src="{{ stu.image }}" >@{{ stu.user }} ({{ stu.name }})</span>
 
 <div id="my">&gt;&gt;{{stu.content}}</div>
</div>
<style>
 #my p {
  display: inline;
 }
 #my {
  margin-left: 2em;
 }
</style>

{% endfor %}

Last updated: {{ site.time }}
