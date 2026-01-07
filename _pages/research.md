---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research centers on two main strands: low-power backscatter communications and intelligent reflecting surface (IRS)-enabled wireless systems, with the overarching goal of enabling sustainable connectivity for resource-constrained IoT devices. In the first strand, I study how backscatter links can support reliable communication under ultra-low-power budgets, focusing on modulation and detection under weak-signal conditions, as well as cooperative and networked backscatter mechanisms in challenging propagation environments. In the second strand, I address key bottlenecks in IRS-enabled systems—such as the high dimensionality of control information, limited generalization across environments, and deployment constraints at edge controllers.

Alongside these core agendas, I maintain an active interest in emerging directions at the intersection of the low-altitude economy and integrated sensing and communication (ISAC), investigating how low-power communication and reconfigurable propagation technologies can be leveraged in UAV-enabled and air–ground collaborative scenarios and what new challenges arise in these highly dynamic environments.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
