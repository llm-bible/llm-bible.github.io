---
layout: publication
title: 'Aquila-plus: Prompt-driven Visual-language Models For Pixel-level Remote Sensing Image Understanding'
authors: Kaixuan Lu
conference: "Arxiv"
year: 2024
bibkey: lu2024aquila
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.06142'}
tags: ['Prompting', 'Tools']
---
The recent development of vision language models (VLMs) has led to
significant advances in visual-language integration through visual instruction
tuning, and they have rapidly evolved in the field of remote sensing image
understanding, demonstrating their powerful capabilities. However, existing
RSVLMs mainly focus on image-level or frame-level understanding, making it
difficult to achieve fine-grained pixel-level visual-language alignment.
Additionally, the lack of mask-based instructional data limits their further
development. In this paper, we propose a mask-text instruction tuning method
called Aquila-plus, which extends the capabilities of RSVLMs to achieve
pixel-level visual understanding by incorporating fine-grained mask regions
into language instructions. To achieve this, we first meticulously constructed
a mask region-text dataset containing 100K samples, and then designed a
visual-language model by injecting pixel-level representations into a large
language model (LLM). Specifically, Aquila-plus uses a convolutional CLIP as
the visual encoder and employs a mask-aware visual extractor to extract precise
visual mask features from high-resolution inputs. Experimental results
demonstrate that Aquila-plus outperforms existing methods in various region
understanding tasks, showcasing its novel capabilities in pixel-level
instruction tuning.
