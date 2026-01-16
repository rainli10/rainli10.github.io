---
title: "Long-term Vision-Language-Navigation with novel scene-graph memory module "
collection: publications
category: Ongoing Projects
permalink: /publication/2026-04-01-thesis
excerpt: 'Current vision-language models often lack fine-grained scene perception and understanding, and they typically do not maintain a structured memory module to store and organize previously observed information. This limitation becomes especially pronounced in long-horizon tasks. In this work, we propose a new scene-graph pipeline that constructs an open-vocabulary, real-time scene graph from streaming visual inputs, enriched with multimodal attributes such as video captions. Moreover, conditioned on a given instruction, our method clusters scene-graph objects and regions to support task-relevant abstraction. Building on this representation, we introduce an LLM-based planning agent that reasons over the continuously updated scene graph to decompose long-horizon instructions, detect execution failures, and perform corrective replanning. The agent then issues more detailed, short-term sub-instructions to a downstream VLN policy for robust task completion.'
date: 2026-04-01
venue: 'Undergraduate Thesis, expected finished by April and submit to conference'
citation: '<strong>Rain Li</strong>; Mingfeng Yuan; Steven Waslander'
header:
  teaser: "accelerometer_teaser.png"
  teaser_hover: "accelerometer_hover.png"
---
Current vision-language models often lack fine-grained scene perception and understanding, and they typically do not maintain a structured memory module to store and organize previously observed information. This limitation becomes especially pronounced in long-horizon tasks. In this work, we propose a new scene-graph pipeline that constructs an open-vocabulary, real-time scene graph from streaming visual inputs, enriched with multimodal attributes such as video captions. Moreover, conditioned on a given instruction, our method clusters scene-graph objects and regions to support task-relevant abstraction. Building on this representation, we introduce an LLM-based planning agent that reasons over the continuously updated scene graph to decompose long-horizon instructions, detect execution failures, and perform corrective replanning. The agent then issues more detailed, short-term sub-instructions to a downstream VLN policy for robust task completion.