---
layout: publication
title: 'Incubating Text Classifiers Following User Instruction With Nothing But LLM'
authors: Letian Peng, Jingbo Shang
conference: "Arxiv"
year: 2024
bibkey: peng2024incubating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10877"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Prompting']
---
In this paper, we aim to generate text classification data given arbitrary
class definitions (i.e., user instruction), so one can train a small text
classifier without any human annotation or raw corpus. Compared with pioneer
attempts, our proposed Incubator is the first framework that can handle
complicated and even mutually dependent classes (e.g., "TED Talk given by
Educator" and "Other"). Specifically, Incubator is an LLM firstly tuned on the
instruction-to-data mappings that we obtained from classification datasets and
descriptions on HuggingFace together with in-context augmentation by GPT-4. We
then refine Incubator by learning on the cluster centers of semantic textual
embeddings to emphasize the uniformity and semantic diversity in generations.
We compare Incubator on various classification tasks with strong baselines such
as direct LLM-based inference and training data generation by prompt
engineering. Experiments show Incubator is able to (1) perform well on
traditional benchmarks, (2) take label dependency and user preference into
consideration, and (3) enable logical text mining by incubating multiple
classifiers.
