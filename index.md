I am a graduate student in Computer Science and Cognitive Science at Tufts University.  My research is primarily focused on the development of morally competent artificial agents.  My long-term research goal is to develop agents that can learn (both from observing others’ behavior and from direct instruction), obey, reason about, and communicate sophisticated (and sometimes conflicting) human moral and social norms.

## Latest posts:

{% capture array_size %}{{ site.posts | size | minus:1 }}{% endcapture %}
{% if array_size contains '-' %}
(no posts yet)
{% else %}
{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** ({{ post.date | date_to_string }})
  {{ post.excerpt }}
{% endfor %}
{% endif %}
