---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
.I'm a Full stack Developer with 2 years of experience in React.
.I'm passionate about Programming and applications.
.I'm currently working on a very secret project.
.I'm also interested in Data analysis and video editing.


<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
