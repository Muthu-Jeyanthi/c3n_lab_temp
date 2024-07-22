---
---
{% capture text %}

<div style="text-align: center; justify-content: center;">

<h3 style="font-size: 2.5em;">Dr. Stefanie Liebe - Cognitive, clinical and computational neuroscience research </h3>
</div>
<p style="font-size: 2.5em;">I am interested in neuroscience research related to vision and memory, while maintaining a close relationship to clinical applications with the potential to provide transferrable insights for understanding neurological disorders with a specific focus on epilepsy. To this end, we use machine-learning methods, and in particular artificial neural networks, to analyse and interpret measurements of neural activity and behaviour.  </p>
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  flip=true
  style="bare"
  text=text
%}

{% include section.html %}

## Highlights

{% capture text %}

We invite you to explore our research projects, which span a range of topics including neural activity during memory processes, the application of artificial intelligence for clinical diagnostics, and advancements in spatial hearing.
{%
  include button.html
  link="research"
  text="See our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Research"
  text=text
%}

{% capture text %}

Access a comprehensive list of our scholarly publications that reflect our ongoing contributions to neuroscience.
{%
  include button.html
  link="publications"
  text="Browse our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="publications"
  title="Our Publications"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Discover the researchers driving our advancements in cognitive and clinical neuroscience.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}


{% include section.html %}
## Funding Agencies

{% include collab_list.html data="funding" component="collab_portrait"%}




