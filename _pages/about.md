---
layout: about
title: about
permalink: /
subtitle: MSc Thesis and HiWi at MPI-SWS, CS at Saarland University

profile:
  align: right
  image: profile_picture_website.jpg
  image_circular: false # crops the image to make it circular
  more_info: >

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

Hey there 👋. I'm a computer science Master student at Saarland University and
member of the [Operating Systems Group](https://os.mpi-sws.org/) at the Max
Planck Institute for Software Systems under the supervision of my namesake
[Antoine Kaufmann](https://people.mpi-sws.org/~antoinek/). There, I am working
on the full-system simulation framework
[SimBricks](https://simbricks.github.io/).

More generally, I enjoy playing around with hard- and software to figure out
what makes a system tick and perform decently. During my time at the university,
I have developed a particular interest in Operating Systems, Distributed
Systems, High-Performance Networking, Software Engineering, as well as some
theory here and there. I enjoy applying the obtained knowledge and combining it
with existing state-of-the-art work to build something even more useful.

Lately, I've been mostly looking into custom hardware development for offloading
intense computations and the high-performance interfaces between hard- and
software that enable significant speed-ups through tight integration.

<br>

<h1 class="post-title">Projects</h1>
<p class="desc">A collection of the projects I am currently working on.</p>

<div class="projects">
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <div class="flex-container">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
</div>

<br>