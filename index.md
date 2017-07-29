I am a graduate student in Computer Science and Cognitive Science at Tufts University.  My research is primarily focused on the development of morally competent artificial agents.  My long-term research goal is to develop agents that can learn (both from observing others’ behavior and from direct instruction), obey, reason about, and communicate sophisticated (and sometimes conflicting) human moral and social norms.  My current research focuses on the problem of planning to obey sometimes-conflicting norms in stochastic domains, where norms are represented in linear temporal logic.

## Latest posts:

{% if site.posts == null %}
(no posts yet)
{% else %}
{% for post in site.posts %}
- [{{post.title}}]({{post.url}}
{% endfor %}
{% endif %}
