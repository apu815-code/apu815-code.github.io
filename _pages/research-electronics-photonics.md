---
layout: page
permalink: /research/electronics-photonics/
title: electronics and photonics
description: Quantum-transport modelling of nanoscale electronic, thermoelectric and optoelectronic devices.
nav: false
---

<p><a href="{{ '/research/' | relative_url }}">← Research</a></p>

<div class="pill-row">
  <span>Quantum transport</span><span>NEGF</span><span>DFT</span><span>Wannier functions</span><span>Topological insulators</span><span>2D materials</span><span>TCAD</span><span>FeFET memory</span><span>SOT memory</span><span>Predictive coding</span><span>CFET</span><span>Photonic biosensors</span><span>PCF-SPR</span><span>Thermoelectrics</span>
</div>

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
    <div class="ico">🧬</div>
    <h3>Materials research</h3>
    <p>First-principles screening and design of 2D, topological and thermoelectric materials: band structure, spin–orbit coupling, Wannier interpolation and topology (Z₂, nodal lines), with attention to contacts, dielectrics and stability.</p>
  </div>
  <div class="feature">
    <div class="ico">🖥️</div>
    <h3>TCAD simulations</h3>
    <p>Device-level simulation in Sentaurus and Silvaco: 3D electrostatics, short-channel and gate-all-around structures, drift-diffusion and hydrodynamic models, calibrated against measurements and atomistic results.</p>
  </div>
  <div class="feature">
    <div class="ico">🧠</div>
    <h3>Ferroelectric FET (FeFET) memory</h3>
    <p>Ferroelectric-gate transistors for non-volatile memory and in-memory computing: polarization switching, retention and endurance, multi-gate and dendritic FeFETs, simulated across TCAD and SPICE.</p>
  </div>
  <div class="feature">
    <div class="ico">🧲</div>
    <h3>SOT memory</h3>
    <p>Spin–orbit-torque magnetic memory: topological-insulator and heavy-metal spin sources, spin textures in Bi₂Se₃-type nanoribbons, and switching efficiency and energy of SOT devices.</p>
  </div>
  <div class="feature">
    <div class="ico">🔁</div>
    <h3>Predictive coding</h3>
    <p>Predictive-coding networks mapped onto device-aware hardware, so that learning rules run on FeFET and other emerging devices with their real non-idealities.</p>
  </div>
  <div class="feature">
    <div class="ico">🧱</div>
    <h3>Complementary FET (CFET)</h3>
    <p>Vertically stacked n- and p-type channels for continued scaling below the nanosheet node: electrostatics, parasitics and variability, studied with TCAD and compact models.</p>
  </div>
  <div class="feature">
    <div class="ico">🧫</div>
    <h3>Photonic biosensors</h3>
    <p>Photonic-crystal-fibre surface-plasmon-resonance (PCF-SPR) sensors with molecularly imprinted polymer (MIP) sensing layers, designed for selective detection of pathogens such as faecal streptococci in drinking water.</p>
  </div>
  <div class="feature">
    <div class="ico">💡</div>
    <h3>Coherent electron–photon interaction</h3>
    <p>Phase-coherent optoelectronics in graphene nanostructures: quantum-interference photodetectors, wavelength-dependent photocurrent switching and nanoscale spectrometers (from my PhD at Georgia Tech).</p>
  </div>
</div>

## Methods and tools

| Layer | Tools |
|---|---|
| Electronic structure | Quantum ESPRESSO (PBE, HSE06, SOC, DFT-D3), Wannier90, WannierTools, Z2Pack |
| Quantum transport | Custom NEGF codes (MATLAB, Python), Landauer–Büttiker, self-consistent Schrödinger–Poisson, phonon dephasing |
| Device / TCAD | Synopsys Sentaurus, Silvaco ATLAS, SPICE, 3D electrostatics |
| Transport theory | BoltzTraP2, drift-diffusion, hydrodynamic and Monte-Carlo comparisons |
