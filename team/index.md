---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

# {% include icon.html icon="fa-solid fa-users" %}Collaborators

{% include section.html %}

{% include collab_list.html data="collab" component="collab_portrait"%}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}


{% endcapture %}

{% include grid.html style="square" content=content %}
