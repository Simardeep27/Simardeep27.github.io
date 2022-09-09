---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* <strong> A Comprehsive Study on Accident Detection Approaches</strong><br>
 Donepudi Harshini S., Jansirani Preethaa,Saxena Mayank,<b>Simardeep Singh Sethi</b>,Yeo Xiong Yun,Barnali Gupta Banik
<br>
IEEE Delhi Section International Conference on Electrical, Electronics and Computer Engineering-2022 <br>
[paper](https://ieeexplore.ieee.org/document/9753079)|[pdf](https://ieeexplore.ieee.org/document/9753079)


MISCELLANEOUS
-----
* Served as a reviewer for <b>The 6th International Conference on Computer Science and Application Engineering(CSAE2022)</b><br>
[certificate](add link)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
