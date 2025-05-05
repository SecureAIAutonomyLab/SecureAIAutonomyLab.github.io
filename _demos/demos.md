---
layout: archive
title: "Demos"
permalink: /demos/
author_profile: true
---

{% include base_path %}
{% for demo in site.demos reversed limit: 10 %}
{% include archive-single.html demo=demo %}
{% endfor %}

<div style="flex: 1 1 45%; border: 1px solid #ddd; padding: 10px;">
  <h3>Demo 1: DigitalTwinUI</h3>
  <p>Explore the core principles and applications of AI agentic systems in the DigitalTwinUI.</p>
  <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <!-- Commented out YouTube iframe for now -->
    <!-- <iframe
      src="https://www.youtube.com/embed/eHEHE2fpnWQ"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
      style="position: absolute; top:0; left:0; width:100%; height:100%;">
    </iframe> -->
    <p>Demo video coming soon!</p>
  </div>
</div>

<div style="flex: 1 1 45%; border: 1px solid #ddd; padding: 10px;">
  <h3>Demo 2: Conceptual Guide: Multi Agent Architectures</h3>
  <p>A walkthrough of different multi-agent system designs and their use cases.</p>
  <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <!-- Commented out YouTube iframe for now -->
    <!-- <iframe
      src="https://www.youtube.com/embed/4nZl32FwU-o"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
      style="position: absolute; top:0; left:0; width:100%; height:100%;">
    </iframe> -->
    <p>Demo video coming soon!</p>
  </div>
</div>
