---
# layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
# <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
# 14{% include base_path %}

---

{% if site.author.googlescholar %}
   
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
