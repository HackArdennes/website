---
permalink: /
layout: main.html

---

# Qui sommes nous

Bienvenue à tous !

## Nos events

{% for event in collections.event %}
- [{{event.data.title}}]({{event.url}})
{% endfor %}
