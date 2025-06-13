---
layout: publication
title: 'Microvqa: A Multimodal Reasoning Benchmark For Microscopy-based Scientific Research'
authors: James Burgess, Jeffrey J Nirschl, Laura Bravo-sánchez, Alejandro Lozano, Sanket Rajan Gupte, Jesus G. Galaz-montoya, Yuhui Zhang, Yuchang Su, Disha Bhowmik, Zachary Coman, Sarina M. Hasan, Alexandra Johannesson, William D. Leineweber, Malvika G Nair, Ridhi Yarlagadda, Connor Zuraski, Wah Chiu, Sarah Cohen, Jan N. Hansen, Manuel D Leonetti, Chad Liu, Emma Lundberg, Serena Yeung-levy
conference: "Arxiv"
year: 2025
bibkey: burgess2025multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13399"}
tags: ['Prompting', 'Multimodal Models', 'Agentic', 'Applications']
---
Scientific research demands sophisticated reasoning over multimodal data, a
challenge especially prevalent in biology. Despite recent advances in
multimodal large language models (MLLMs) for AI-assisted research, existing
multimodal reasoning benchmarks only target up to college-level difficulty,
while research-level benchmarks emphasize lower-level perception, falling short
of the complex multimodal reasoning needed for scientific discovery. To bridge
this gap, we introduce MicroVQA, a visual-question answering (VQA) benchmark
designed to assess three reasoning capabilities vital in research workflows:
expert image understanding, hypothesis generation, and experiment proposal.
MicroVQA consists of 1,042 multiple-choice questions (MCQs) curated by biology
experts across diverse microscopy modalities, ensuring VQA samples represent
real scientific practice. In constructing the benchmark, we find that standard
MCQ generation methods induce language shortcuts, motivating a new two-stage
pipeline: an optimized LLM prompt structures question-answer pairs into MCQs;
then, an agent-based `RefineBot' updates them to remove shortcuts. Benchmarking
on state-of-the-art MLLMs reveal a peak performance of 53%; models with
smaller LLMs only slightly underperform top models, suggesting that
language-based reasoning is less challenging than multimodal reasoning; and
tuning with scientific articles enhances performance. Expert analysis of
chain-of-thought responses shows that perception errors are the most frequent,
followed by knowledge errors and then overgeneralization errors. These insights
highlight the challenges in multimodal scientific reasoning, showing MicroVQA
is a valuable resource advancing AI-driven biomedical research. MicroVQA is
available at https://huggingface.co/datasets/jmhb/microvqa, and project page at
https://jmhb0.github.io/microvqa.
