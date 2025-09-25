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
Among various single-molecule localization microscopy techniques (SMLM), 4Pi-SMLM uses interferometric detection to achieve ultra-high axial resolution. In 4Pi-SMLM, the sample is sandwiched between two objectives, and the fluorescence of single fluorophores collected by the two opposing objectives is interfered at a beam splitter. The z position of the fluorophore determines the path difference between the two interferometer arms, leading to constructive or destructive interference. The central intensity of the 4Pi point spread function (4Pi-PSF) is thus modulated with the emitter's axial position at a period of approximately λ/2. The twofold increase in collected photons, combined with this strong intensity modulation, results in a 5–7-fold increase in the axial resolution compared to single-objective SMLM. Our lab is interested in constructing a 4Pi-SMLM system and use it to study various questions in cellular biology.
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


{% capture proj3 %}
In fluorescence microscopy, we use various methods to measure the paremeters of single molecules, such as their positions, separations, and orientations. Given a particular imaging system, the estimation precision of a set of unknown parameters is bounded by the classical Cramér-Rao lower Bound (CRB). One important test to evaluate a localization algorithm is to test how close it can achieve the CRB. While CRB is dependent on the measurement technique, quantum information theory provides a lower bound for any possible measurement of a parameter, the quantum CRB (QCRB). The QCRB depends on the emitter type and parameters to be measured, but is independent of any particular measurement strategy. Therefore, QCRB is the lower bound for all measurement techniques. Finding a measurement technique that saturates this bound is a fundamental goal in quantum metrology. Our lab is interested in applying quantum information theory in fluorescence microscopy.
{% endcapture %}

{%
  include feature.html
  image="images/research/qcrb.png"
  link="research"
  title="Quantum information theory in fluorescence microscopy"
  text=proj3
%}

{% 
  include citation.html 
  lookup="Separation estimation of two freely rotating dipole emitters near the quantum limit" 
%}