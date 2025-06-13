---
layout: publication
title: 'LANTERN++: Enhancing Relaxed Speculative Decoding With Static Tree Drafting For Visual Auto-regressive Models'
authors: Sihwan Park, Doohyuk Jang, Sungyub Kim, Souvik Kundu, Eunho Yang
conference: "Arxiv"
year: 2025
bibkey: park2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06352"}
  - {name: "Code", url: "https://github.com/jadohu/LANTERN"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Has Code']
---
Speculative decoding has been widely used to accelerate auto-regressive (AR)
text generation. However, its effectiveness for visual AR models remains
limited due to token selection ambiguity, where multiple tokens share similarly
low probabilities and thus reduce acceptance rates. Recently, relaxed
speculative decoding with dynamic tree drafting was proposed to mitigate this
ambiguity, demonstrating promising results in accelerating visual AR models.
However, we observe that token selection ambiguity still negatively affects
dynamic tree drafting, resulting in shallow draft trees and limited
acceleration. To overcome this issue, we introduce LANTERN++, a refined
framework that integrates static tree drafting with a tailored relaxed
acceptance condition, allowing drafts to be selected independently of
low-confidence predictions. This enables the acceptance of deeper sequences,
improving decoding efficiency while preserving image quality. Extensive
experiments on state-of-the-art visual AR models demonstrate that LANTERN++
significantly accelerates inference, achieving up to \\(\mathbf\{\times 2.56\}\\)
speedup over standard AR decoding while maintaining high image quality. The
code is publicly available at https://github.com/jadohu/LANTERN.
