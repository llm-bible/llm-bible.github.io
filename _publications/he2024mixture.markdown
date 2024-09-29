---
layout: publication
title: MARS Mixture Of Auto45;regressive Models For Fine45;grained Text45;to45;image Synthesis
authors: He Wanggui, Fu Siming, Liu Mushui, Wang Xierui, Xiao Wenyi, Shu Fangxun, Wang Yi, Zhang Lei, Yu Zhelun, Li Haoyuan, Huang Ziwei, Gan Leilei, Jiang Hao
conference: "Arxiv"
year: 2024
bibkey: he2024mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07614"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'Merging', 'Prompting', 'Tools', 'Training Techniques']
---
Auto45;regressive models have made significant progress in the realm of language generation yet they do not perform on par with diffusion models in the domain of image synthesis. In this work we introduce MARS a novel framework for T2I generation that incorporates a specially designed Semantic Vision45;Language Integration Expert (SemVIE). This innovative component integrates pre45;trained LLMs by independently processing linguistic and visual information freezing the textual component while fine45;tuning the visual component. This methodology preserves the NLP capabilities of LLMs while imbuing them with exceptional visual understanding. Building upon the powerful base of the pre45;trained Qwen45;7B MARS stands out with its bilingual generative capabilities corresponding to both English and Chinese language prompts and the capacity for joint image and text generation. The flexibility of this framework lends itself to migration towards any45;to45;any task adaptability. Furthermore MARS employs a multi45;stage training strategy that first establishes robust image45;text alignment through complementary bidirectional tasks and subsequently concentrates on refining the T2I generation process significantly augmenting text45;image synchrony and the granularity of image details. Notably MARS requires only 937; of the GPU days needed by SD1.5 yet it achieves remarkable results across a variety of benchmarks illustrating the training efficiency and the potential for swift deployment in various applications.
