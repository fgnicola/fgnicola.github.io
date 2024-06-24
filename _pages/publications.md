---
layout: archive
title: "Books"
permalink: /books/
author_profile: true
---

#{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=680281">my SSRN profile</a>.</div>
#{% endif %}

#{% include base_path %}

#{% for post in site.publications reversed %}
  {% include archive-single.html %}
#{% endfor %}
