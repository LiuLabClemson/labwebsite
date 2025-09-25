---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{%
  include button.html
  type="email"
  text="shengl@clemson.edu"
  link="shengl@clemson.edu"
%}



{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Kinard+Laboratory+of+Physics/@34.6775959,-82.8349358,212m/data=!3m1!1e3!4m6!3m5!1s0x88585e6c4ff4f221:0x96bbad4c6036c748!8m2!3d34.6775644!4d-82.8351009!16s%2Fg%2F11b7q9d7v0?entry=ttu&g_ep=EgoyMDI1MDkyMy4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Office: Kinard Lab 204  

Delta Epsilon Ct  

Clemson, SC 29634

{% endcapture %}

{% capture col2 %}
Lab: Jordan Hall G02A 
Delta Epsilon Ct  
Clemson, SC 29634

{% endcapture %}



{% include cols.html col1=col1 col2=col2%}
