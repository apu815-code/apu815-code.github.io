---
layout: page
permalink: /research/
title: research
description: Computational nanoelectronics, from first-principles materials physics to transistor-level device simulation.
nav: true
nav_order: 1
dropdown: true
children:
  - title: Electronics and Photonics
    match: electronics and photonics
    permalink: /research/electronics-photonics/
  - title: Power
    match: power
    permalink: /research/power/
---

## Research theme: multiscale device transport

Modern nanoscale devices are designed with a chain of models. Density functional theory gives the material, Wannier functions give a compact Hamiltonian, non-equilibrium Green's function (NEGF) transport gives the current, and TCAD gives the circuit-relevant device. A number that comes out at the end is only as trustworthy as every parameter that went in. My group works to make that chain **quantitative, reproducible and traceable**. We track the origin and uncertainty of each parameter, and we test which claims about a new material survive contact with realistic dielectrics, contacts and disorder.

## Two research branches

<div class="feature-grid">
  <div class="feature">
    <div class="ico">🔬</div>
    <h3><a href="{{ '/research/electronics-photonics/' | relative_url }}">Electronics and Photonics →</a></h3>
    <p>Topological-insulator FETs, 2D-material transistors, thermoelectrics, ferroelectric neuromorphic hardware and coherent electron–photon devices, studied with DFT, Wannier, NEGF and TCAD.</p>
  </div>
  <div class="feature">
    <div class="ico">🔌</div>
    <h3><a href="{{ '/research/power/' | relative_url }}">Power →</a></h3>
    <p>Wireless EV charging, drive electronics and reliability, and power-system planning with distributed solar generation.</p>
  </div>
</div>

## Selected publications

{% include selected_papers.liquid %}

[Full publication list →]({{ '/publications/' | relative_url }}) · [Google Scholar](https://scholar.google.com/citations?user=5dlRXsAAAAAJ)

## Interactive tools

Some of my models are packaged as browser-based [applets]({{ '/applets/' | relative_url }}) you can play with.
