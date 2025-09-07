---
title: Resources
nav:
  order: 4
  tooltip: Softwares, useful links
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research Projects

## Current Projects
Summary of current projects

{% capture text %}

Single particle tracking using Minflux 

{%
  include button.html
  link="research"
  text="See more info"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="MINFLUX"
  text=text
%}





{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
