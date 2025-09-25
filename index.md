---
---

# Liu Lab Clemson's Website

Our lab is focused on developing advanced microscope systems to study protein interactions and organizations at high spatiotemporal resolution. 

{% include section.html %}

## Highlights

{% capture text %}

Our lab is interested in developing microscope systems based on MINFLUX and 4Pi-SMLM, and exploring quantum information in fluorescence microscopy.

{%
  include button.html
  link="research"
  text="See our research areas"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/homepage/nup96_4pi.png"
  link="research"
  title="Our Research"
  text=text
%}



{% capture text %}
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
  image="images/homepage/cooperlib.png"
  link="team"
  title="Our Team"
  flip=true
  text=text
%}




{% capture text %}

{%
  include button.html
  link="resources"
  text="Browse useful tools"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.png"
  link="resources"
  title="Tools"
  style="bare"
  text=text
%}
