---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-8MRNDHYLKN"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-8MRNDHYLKN');
</script>

{% if site.author.googlescholar %}
<div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}