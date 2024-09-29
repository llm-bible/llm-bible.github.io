---
layout: publication
title: CURATRON\: Complete Robust Preference Data For Robust Alignment Of Large Language Models
authors: Nguyen Son The, Naresh Niranjan Uma, Tulabandhula Theja
conference: "Arxiv"
year: 2024
bibkey: nguyen2024complete
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02745"}
tags: ['Reinforcement Learning', 'Security']
---
This paper addresses the challenges of aligning large language models (LLMs) with human values via preference learning (PL) with a focus on the issues of incomplete and corrupted data in preference datasets. We propose a novel method for robustly and completely recalibrating values within these datasets to enhance LLMs resilience against the issues. In particular we devise a guaranteed polynomial time ranking algorithm that robustifies several existing models such as the classic Bradley--Terry--Luce (BTL) (Bradley and Terry 1952) model and certain generalizations of it. To the best of our knowledge our present work is the first to propose an algorithm that provably recovers an (epsilon)-optimal ranking with high probability while allowing as large as O(n) perturbed pairwise comparison results per model response. Furthermore we show robust recovery results in the partially observed setting. Our experiments confirm that our algorithms handle adversarial noise and unobserved comparisons well in both general and LLM preference dataset settings. This work contributes to the development and scaling of more reliable and ethically aligned AI models by equipping the dataset curation pipeline with the ability to handle missing and maliciously manipulated inputs.
