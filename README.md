
# Contributors3
  collection:
  _stu:
    output : true
{% for _stu in site.stu %}

 <h2> {{ _stu.image }}@{{ _stu.user }}({{ _stu.name | markdownify }}) </h2>
 <h3>{{_stu.content}}</h3>
 
{% endfor %}

Last updated: {{ site.time }}
