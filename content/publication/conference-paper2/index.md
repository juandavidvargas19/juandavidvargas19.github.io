---
title: 'MAPLE: Modular Attention for Interpretable and Prosocial Multi-Agent Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zahra Sheikhbahaee
  - Chang Su
  - Aniket Rajiv Didolkar
  - admin
  - Manoosh Samiei
  - Leonardo Christov-Moore
  - Nicco Reggente
  - Dianbo Liu
  - Irina Rish
  - Guillaume Dumas
    
date: '2025-03-01'

# Schedule page publish date (NOT publication's date).

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Submitted to RLC 2025

abstract: |
  We propose a novel approach to enhance interpretability and performance in multi-agent reinforcement learning (MARL) through modular architecture and representation learning. We introduce **MAPLE** (Modular Attention for Prosocial Learning), a MARL architecture built on Independent Proximal Policy Optimization (IPPO) with brain-inspired modular processing that mirrors the functional specialization observed in human neural systems.

  We incorporate a pre-trained slot attention model to learn compositional, object-centric representations, along with modular recurrent networks that interact through an attention bottleneck, consistently outperforming end-to-end RL across different environments. Our architecture incorporates three key mechanisms to address challenges in complex social scenarios:

  1. Learning orthogonal latent representations and directing them through modular recurrent neural networks, allowing different modules to specialize in processing distinct environmental features.
  2. Enabling generalization via compositional consistency loss for slot attention modules.
  3. Using different fine-tuning approaches such as LoRA and progressively unfreezing parts of the slot attention module during RL training, allowing pretrained representations to adapt while maintaining their specialized structure.

  Moreover, we integrate modular Recurrent Independent Mechanisms (RIMs) in agents' value networks, encouraging sparsity and fast adaptation to changing environments, with modules dynamically activating based on relevant environmental contexts. This unique combination of attention mechanisms and modular processing results in specialized neural components that focus on different environmental aspects, thus improving coordination, generalization, and interpretability.

  We evaluate MAPLE in DeepMind's Melting Pot suite across three environments: mixed strategies (Prisoner's Dilemma), social good (Allelopathic Harvest), and resource management (Territory Room). Our results demonstrate that MAPLE not only enhances performance but also reveals emergent social capabilities across environments while providing deeper insights into the learned representations driving agent behaviors.

# Summary. An optional shortened abstract.
summary: MAPLE introduces a novel approach to enhancing interpretability and performance in multi-agent reinforcement learning (MARL) through modular architecture and representation learning.

tags:
  - Reinforcement Learning

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://drive.google.com/file/d/1aEcKU-kzjo8WxM_sjoJr9HGxAzQRVw4g/view?usp=sharing'
url_code: ''
url_poster: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '[MAPLE](project2.jpg)'
  focal_point: ''
  preview_only: false


---
