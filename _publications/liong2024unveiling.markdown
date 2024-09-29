---
layout: publication
title: Unveiling Vulnerability Of Self45;attention
authors: Liong Khai Jiet, Wu Hongqiu, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: liong2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16470"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Transformer']
---
Pre45;trained language models (PLMs) are shown to be vulnerable to minor word changes which poses a big threat to real45;world systems. While previous studies directly focus on manipulating word inputs they are limited by their means of generating adversarial samples lacking generalization to versatile real45;world attack. This paper studies the basic structure of transformer45;based PLMs the self45;attention (SA) mechanism. (1) We propose a powerful perturbation technique textit123;HackAttend125; which perturbs the attention scores within the SA matrices via meticulously crafted attention masks. We show that state45;of45;the45;art PLMs fall into heavy vulnerability that minor attention perturbations (137;) can produce a very high attack success rate (9837;). Our paper expands the conventional text attack of word perturbations to more general structural perturbations. (2) We introduce textit123;S45;Attend125; a novel smoothing technique that effectively makes SA robust via structural perturbations. We empirically demonstrate that this simple yet effective technique achieves robust performance on par with adversarial training when facing various text attackers. Code is publicly available at url123;github.com/liongkj/HackAttend125;.
