---
layout: publication
title: 'TDRI: Two-phase Dialogue Refinement And Co-adaptation For Interactive Image Generation'
authors: Yuheng Feng, Jianhui Wang, Kun Li, Sida Li, Tianyu Shi, Haoyue Han, Miao Zhang, Xueqian Wang
conference: "Arxiv"
year: 2025
bibkey: feng2025two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17669"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'GPT', 'Prompting', 'Applications']
---
Although text-to-image generation technologies have made significant
advancements, they still face challenges when dealing with ambiguous prompts
and aligning outputs with user intent.Our proposed framework, TDRI (Two-Phase
Dialogue Refinement and Co-Adaptation), addresses these issues by enhancing
image generation through iterative user interaction. It consists of two phases:
the Initial Generation Phase, which creates base images based on user prompts,
and the Interactive Refinement Phase, which integrates user feedback through
three key modules. The Dialogue-to-Prompt (D2P) module ensures that user
feedback is effectively transformed into actionable prompts, which improves the
alignment between user intent and model input. By evaluating generated outputs
against user expectations, the Feedback-Reflection (FR) module identifies
discrepancies and facilitates improvements. In an effort to ensure consistently
high-quality results, the Adaptive Optimization (AO) module fine-tunes the
generation process by balancing user preferences and maintaining prompt
fidelity. Experimental results show that TDRI outperforms existing methods by
achieving 33.6% human preference, compared to 6.2% for GPT-4 augmentation, and
the highest CLIP and BLIP alignment scores (0.338 and 0.336, respectively). In
iterative feedback tasks, user satisfaction increased to 88% after 8 rounds,
with diminishing returns beyond 6 rounds. Furthermore, TDRI has been found to
reduce the number of iterations and improve personalization in the creation of
fashion products. TDRI exhibits a strong potential for a wide range of
applications in the creative and industrial domains, as it streamlines the
creative process and improves alignment with user preferences
