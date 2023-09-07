---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="Email us"
  link="jielun.zhang@und.edu"
%}
{%
  include button.html
  type="phone"
  text="(701) 777-4986"
  link="+1-701-777-4986"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/University+of+North+Dakota:+Tech+Accelerator/@47.919118,-97.0929666,17z/data=!3m1!4b1!4m6!3m5!1s0x52c6810c8212278f:0x48ffc2c89e554ea8!8m2!3d47.9191144!4d-97.0903917!16s%2Fg%2F11cp7jbh05?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/und-tech.jpeg"
  caption="UND Tech Accelerator"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/und-tech-add.png"
  caption="Tech Accelerator on map"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Tech Accelerator 
4201 James Ray Dr
Grand Forks ND 58202
{% endcapture %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}
