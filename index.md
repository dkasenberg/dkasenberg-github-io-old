I am a graduate student in Computer Science and Cognitive Science at Tufts University.  My research is primarily focused on the development of morally competent artificial agents.  My long-term research goal is to develop agents that can learn (both from observing others’ behavior and from direct instruction), obey, reason about, and communicate sophisticated (and sometimes conflicting) human moral and social norms.

## Latest posts:

{% capture array_size %}{{ site.posts | size | minus:1 }}{% endcapture %}
{% if array_size contains '-' %}
(no posts yet)
{% else %}



<table>
{% for post in site.posts %}
<tr>
<td>{% if post.thumbnail %}
<a href="{{ post.url }}">
<img src="{{ post.thumbnail }}" class="thumbnail" /></a>
{% endif %}
</td>
<td>
<span class="post-title-link">
<a href="{{ post.url }}">{{ post.title }}</a>
</span>({{ post.date | date_to_string }}){{ post.excerpt }}
  </td>
</tr>
{% endfor %}
</table>
{% endif %}
