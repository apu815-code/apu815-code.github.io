---
layout: page
title: Quantum tunneling through a rectangular barrier
description: Compute the exact transmission probability T(E) for an electron crossing a barrier. Vary height, width and effective mass.
importance: 1
tags: [quantum transport, teaching, tunneling]
applet_src: /assets/applets/barrier-tunneling/index.html
applet_height: 720
---

<div class="applet-meta">
  <span class="badge-soft">Interactive</span>
  <span class="badge-soft">Browser-based</span>
</div>

<iframe class="applet-frame" src="{{ page.applet_src | relative_url }}" height="{{ page.applet_height }}" loading="lazy" title="{{ page.title }}"></iframe>

## About this applet

The applet evaluates the exact transfer-matrix result for a single rectangular potential barrier of height $V_0$ and width $a$ in the effective-mass approximation:

$$
T(E)=\left[1+\frac{V_0^2\,\sinh^2(\kappa a)}{4E(V_0-E)}\right]^{-1},\qquad
\kappa=\frac{\sqrt{2m^*(V_0-E)}}{\hbar}\quad (E<V_0),
$$

with the corresponding oscillatory form above the barrier. It is a starting point for understanding tunneling in the band-to-band and Schottky-barrier transport that limits nanoscale FETs.

[Open the applet in its own window]({{ page.applet_src | relative_url }}){: target="_blank"}
