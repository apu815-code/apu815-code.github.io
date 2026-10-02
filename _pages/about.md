---
layout: about
title: about
permalink: /
subtitle: >
  Professor, <a href="https://eee.buet.ac.bd/">Department of Electrical and Electronic Engineering</a>,
  <a href="https://www.buet.ac.bd/">Bangladesh University of Engineering and Technology (BUET)</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Room ECE 427, ECE Building</p>
    <p>Department of EEE, BUET</p>
    <p>Dhaka 1205, Bangladesh</p>
    <p>PABX: 6566</p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 6

latest_posts:
  enabled: false
---

I am a Professor in the Department of Electrical and Electronic Engineering at BUET, where I have taught since 1999. My research is in **computational nanoelectronics**. I study how electrons move through nanoscale and quantum materials, and how that transport can be turned into devices: transistors, detectors and energy converters.

The core of my group's work is a **first-principles-to-device simulation chain**. It starts with density functional theory (Quantum ESPRESSO), uses maximally localized Wannier functions to build tight-binding Hamiltonians (Wannier90, Z2Pack), feeds them to non-equilibrium Green's function (NEGF) quantum transport, and scales up to TCAD device simulation (Sentaurus, Silvaco).

Current topics include:

- **Topological-insulator FETs:** gate-field-driven quantum spin Hall to trivial transitions in 1T′-MoS₂, 1T′-WTe₂, stanene, Bi₄X₄ (X = Br, I) and Bi₂Se₃ nanoribbons
- **2D-material transistors and contacts:** borophene, black phosphorus, graphene nanoribbons, graphynes, bismuthene and MoSe₂ nanoribbons, and Fermi-level pinning at metal/2D contacts such as NbₓW₁₋ₓSe₂/WSe₂
- **Materials research and thermoelectrics:** first-principles screening of 2D and topological materials, and strain- and pressure-engineered Bi₂Te₃
- **TCAD simulations and CFET:** Sentaurus/Silvaco device simulation, gate-all-around and complementary FET structures
- **FeFET and SOT memory, predictive coding:** device-aware neuromorphic and in-memory hardware
- **Photonic biosensors:** PCF-SPR sensors with molecularly imprinted polymer layers
- **Coherent electron–photon interaction** in graphene nanostructures (my PhD work at Georgia Tech on quantum-interference photodetectors)
- **Power systems:** wireless EV charging, automatic voltage regulators, solar PV integration, and grid simulation with machine-learning prediction of power-plant derating

<p><a class="btn btn-sm z-depth-0" role="button" href="{{ '/research/' | relative_url }}">Research</a></p>

<script id="pubfix">
  /* Selected publications heading: plain text (not a link) with a separate, clickable "All publications" button beside it */
  document.addEventListener('DOMContentLoaded', function () {
    var h = Array.prototype.slice.call(document.querySelectorAll('h2')).filter(function (e) { return /selected publications/i.test(e.textContent); })[0];
    if (!h) return;
    var a = h.querySelector('a');
    var url = a ? a.getAttribute('href') : '/publications/';
    h.textContent = 'selected publications';
    var b = document.createElement('a');
    b.href = url; b.textContent = 'All publications'; b.className = 'btn btn-sm z-depth-0'; b.setAttribute('role', 'button');
    b.style.cssText = 'margin-left:1rem;font-size:0.9rem;vertical-align:middle;background:#003057;color:#fff;border:1px solid #b3a369;border-radius:6px;padding:0.35rem 0.8rem;';
    h.appendChild(b);
  });
</script>

Outside research, I provide **engineering consultancy** through the Bureau of Research, Testing and Consultation (BRTC), BUET. This includes forensic investigation of electrical fires, product testing and reliability assessment, technical committee work for government agencies, and recruitment examinations for public-sector utilities. See [consultancy](/consultancy/) for details.

I received my Ph.D. from the School of Electrical and Computer Engineering at the **Georgia Institute of Technology** (2016), and my M.Sc. (2006) and B.Sc. (1999) in EEE from **BUET**.

**Prospective students:** I supervise B.Sc. (EEE 400) and M.Sc. theses in quantum transport, first-principles device modeling and TCAD. Students with a strong background in solid-state physics, programming (Python or MATLAB) or Linux-based scientific computing are encouraged to get in touch.
