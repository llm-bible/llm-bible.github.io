---
layout: publication
title: 'Universal Cross-tokenizer Distillation Via Approximate Likelihood Matching'
authors: Benjamin Minixhofer, Ivan Vulić, Edoardo Maria Ponti
conference: "Arxiv"
year: 2025
bibkey: minixhofer2025universal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20083"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Distillation']
---
Distillation has shown remarkable success in transferring knowledge from a Large Language Model (LLM) teacher to a student LLM. However, current distillation methods require similar tokenizers between the teacher and the student, restricting their applicability to only a small subset of teacher-student pairs. In this work, we develop a principled cross-tokenizer distillation method to solve this crucial deficiency. Our method is the first to enable effective distillation across fundamentally different tokenizers, while also substantially outperforming prior methods in all other cases. We verify the efficacy of our method on three distinct use cases. First, we show that viewing tokenizer transfer as self-distillation enables unprecedentedly effective transfer across tokenizers, including rapid transfer of subword models to the byte-level. Transferring different models to the same tokenizer also enables ensembling to boost performance. Secondly, we distil a large maths-specialised LLM into a small general-purpose model with a different tokenizer, achieving competitive maths problem-solving performance. Thirdly, we use our method to train state-of-the-art embedding prediction hypernetworks for training-free tokenizer transfer. Our results unlock an expanded range of teacher-student pairs for distillation, enabling new ways to adapt and enhance interaction between LLMs.
