---
title: Lab Member
nav:
  order: 3
  tooltip: About our lab members
---

# {% include icon.html icon="fa-solid fa-users" %}Lab Members



{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ms" %}


# {% include icon.html icon="fa-solid fa-users" %}External collaborators
{% include list.html data="members" component="portrait" filters="role: ec" %}

{% include section.html%}


Photos of lab activities will be posted below.
{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
