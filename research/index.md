---
title: Research
nav:
  order: 1
  tooltip: Past and ongoing research projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research Projects

## Current Projects
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


{% capture proj2 %}
4Pi-SMLM
{% endcapture %}

{%
  include feature.html
  image="images/research/4pi-smlm.png"
  link="research"
  title="4Pi-SMLM"
  text=proj2
%}

{% 
  include citation.html 
  lookup="Universal inverse modeling of point spread functions for SMLM localization and microscope characterization" 
%}

{% 
  include citation.html 
  lookup="Enhanced 4Pi single-molecule localization microscopy with coherent pupil based localization" 
%}

{% 
  include citation.html 
  lookup="Global fitting for high-accuracy multi-channel single-molecule localization" 
%}
