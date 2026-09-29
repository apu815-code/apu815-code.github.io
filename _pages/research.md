---
layout: page
permalink: /research/
title: research
description: Computational nanoelectronics, from first-principles materials physics to transistor-level device simulation.
nav: true
nav_order: 1
---

<div class="pill-row">
  <span>Quantum transport</span><span>NEGF</span><span>DFT</span><span>Wannier functions</span><span>Topological insulators</span><span>2D materials</span><span>TCAD</span><span>FeFET</span><span>Thermoelectrics</span>
</div>

## Research theme: parameter provenance in multiscale device transport

Modern nanoscale devices are designed with a chain of models. Density functional theory gives the material, Wannier functions give a compact Hamiltonian, non-equilibrium Green's function (NEGF) transport gives the current, and TCAD gives the circuit-relevant device. A number that comes out at the end is only as trustworthy as every parameter that went in. My group works to make that chain **quantitative, reproducible and traceable**. We track the origin and uncertainty of each parameter, and we test which claims about a new material survive contact with realistic dielectrics, contacts and disorder.

## Research directions

<div class="feature-grid">
  <div class="feature">
    <div class="ico">🧭</div>
    <h3>Topological-insulator FETs</h3>
    <p>Gate-field-driven quantum spin Hall to trivial transitions in 1T′-MoS₂, 1T′-WTe₂, stanene and Bi₄X₄ (X = Br, I) nanoribbons, and how helical edge conduction and Kramers protection behave under disorder and realistic gate stacks.</p>
  </div>
  <div class="feature">
    <div class="ico">🧊</div>
    <h3>2D-material transistors</h3>
    <p>Borophene, black phosphorus (gate-all-around nanosheets), graphene nanoribbons, graphynes, bismuthene and MoSe₂ nanoribbons. We look at electric-field-induced gap engineering and short-channel limits.</p>
  </div>
  <div class="feature">
    <div class="ico">🔥</div>
    <h3>Thermoelectric materials</h3>
    <p>Pressure- and strain-engineered Bi₂Te₃ and related topological thermoelectrics, using DFT + spin-orbit coupling and Boltzmann transport (BoltzTraP2).</p>
  </div>
  <div class="feature">
    <div class="ico">🧠</div>
    <h3>Ferroelectric FETs and neuromorphic hardware</h3>
    <p>Device-aware learning hardware: dendritic multi-gate FeFETs simulated across TCAD, SPICE and spiking networks, with attention to device non-idealities.</p>
  </div>
  <div class="feature">
    <div class="ico">💡</div>
    <h3>Coherent electron–photon interaction</h3>
    <p>Phase-coherent optoelectronics in graphene nanostructures: quantum-interference photodetectors, wavelength-dependent photocurrent switching and nanoscale spectrometers (from my PhD at Georgia Tech).</p>
  </div>
  <div class="feature">
    <div class="ico">🔌</div>
    <h3>Power and energy electronics</h3>
    <p>Wireless charging of electric vehicles, and drive electronics with reliability-driven design (see <a href="/consultancy/">consultancy</a>).</p>
  </div>
</div>

## Methods and tools

| Layer | Tools |
|---|---|
| Electronic structure | Quantum ESPRESSO (PBE, HSE06, SOC, DFT-D3), Wannier90, WannierTools, Z2Pack |
| Quantum transport | Custom NEGF codes (MATLAB, Python), Landauer–Büttiker, self-consistent Schrödinger–Poisson, phonon dephasing |
| Device / TCAD | Synopsys Sentaurus, Silvaco ATLAS, SPICE, 3D electrostatics |
| Transport theory | BoltzTraP2, drift-diffusion, hydrodynamic and Monte-Carlo comparisons |

## Selected publications

{% include selected_papers.liquid %}

[Full publication list →](/publications/) · [Google Scholar](https://scholar.google.com/citations?user=5dlRXsAAAAAJ)

## Interactive tools

Some of my models are packaged as browser-based [applets](/applets/) you can play with.
