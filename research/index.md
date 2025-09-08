---
title: Research
nav:
  order: 1
  tooltip: Past and ongoing research projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research Projects

## Current Projects
Summary of current projects

{% capture proj1 %}
MINFLUX (minimum photon flux) employs a donut shaped laser beam to track the emitter with the local minimum of its illumination pattern. The central minimum of a donut-shaped beam is scanned around the single emitter following a predefined scanning pattern. The photon values detected at all scanning positions, together with the knowledge of the scanning pattern, allow one to extract the emitter's position with nanometer precision. In single-particle tracking, the donut beam continuously follows the emitter with a localization rate up to the scanning cycle rate of approximately 10 kHz. Our lab is interested in constructing a custom-built MINFLUX system and applying it to studying protein dynamics on cells. 
{% endcapture %}

{%
  include feature.html
  image="images/research/minflux.png"
  link="research"
  title="MINFLUX"
  text=proj1
%}

{% 
  include citation.html 
  lookup="Direct observation of motor protein stepping in living cells using MINFLUX" 
%}



{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
