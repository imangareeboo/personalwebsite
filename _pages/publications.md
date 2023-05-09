---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Rollins College Publications
-----
2018 "Mauritian Literature versus the Cambridge International Education System," *Honor Program Thesis* 
 [*Rollins Scholarship Online*](https://scholarship.rollins.edu/honors/72/)<br>
2018 "Lost and Frustrated" *The Independent* Edition 5, Issue 2<br>
2017 "What Ta-Nehisi Coates Revealed About the Liberal Arts of Rollins College" *The Independent* Edition 5, Issue 1<br>
[Access *The Independent* Online](https://issuu.com/theindependentmag/docs/the_independent_mag_issue_10_online)

High School Magazine
-----
"The Truth About Love" in collaboration with Ayana Vilmenay and Brianna Feliciano in University High School Literary Magazine

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
