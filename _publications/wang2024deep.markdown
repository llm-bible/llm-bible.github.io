---
layout: publication
title: 'DRT: Deep Reasoning Translation Via Long Chain-of-thought'
authors: Jiaan Wang, Fandong Meng, Yunlong Liang, Jie Zhou
conference: "Arxiv"
year: 2024
bibkey: wang2024deep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17498"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Recently, O1-like models have emerged as representative examples,
illustrating the effectiveness of long chain-of-thought (CoT) in reasoning
tasks such as math and coding tasks. In this paper, we introduce DRT, an
attempt to bring the success of long CoT to neural machine translation (MT).
Specifically, in view of the literature books that might involve similes and
metaphors, translating these texts to a target language is very difficult in
practice due to cultural differences. In such cases, literal translation often
fails to convey the intended meaning effectively. Even for professional human
translators, considerable thought must be given to preserving semantics
throughout the translation process. To simulate LLMs' long thought ability in
MT, we first mine sentences containing similes or metaphors from existing
literature books, and then develop a multi-agent framework to translate these
sentences via long thought. In the multi-agent framework, a translator is used
to iteratively translate the source sentence under the suggestions provided by
an advisor. To ensure the effectiveness of the long thoughts, an evaluator is
also employed to quantify the translation quality in each round. In this way,
we collect tens of thousands of long-thought MT data, which is used to train
our DRT. Using Qwen2.5 and LLama-3.1 as the backbones, DRT models can learn the
thought process during machine translation, and outperform vanilla LLMs as well
as LLMs which are simply fine-tuning on the paired sentences without long
thought, showing its effectiveness.
