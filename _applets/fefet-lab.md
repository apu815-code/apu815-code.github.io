---
layout: page
title: FeFET Lab
description: "An interactive ferroelectric-memory lab: switching, memory window and read/write behaviour of a FeFET."
importance: 3
tags: [FeFET, memory, teaching]
applet_src: /assets/applets/mem.html
applet_height: 1000
---

<div class="applet-meta">
  <span class="badge-soft">Interactive</span>
  <span class="badge-soft">Browser-based</span>
</div>

<iframe class="applet-frame" src="{{ page.applet_src | relative_url }}" height="{{ page.applet_height }}" loading="lazy" title="{{ page.title }}" onload="var f=this;function r(){try{f.style.height=(f.contentWindow.document.documentElement.scrollHeight+20)+'px'}catch(e){}}r();setInterval(r,1500)"></iframe>

[Open the applet in its own window]({{ page.applet_src | relative_url }}){: target="_blank"}
