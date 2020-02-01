---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=U7HARQEAAAAJ&hl=en">my Google Scholar profile</a> and <a href="https://www.researchgate.net/profile/Ei_Pa_Pa_Pe-Than">my Research Gate profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
