---
layout: home
---

# All blue nerds:
{% for blues in site.data.bluenerd.bluenerds %}

**Name:** {{blues.name}}
**Species:** {{blues.species}}

{% endfor %}
