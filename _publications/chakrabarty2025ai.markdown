---
layout: publication
title: 'Ai-slop To Ai-polish? Aligning Language Models Through Edit-based Writing Rewards And Test-time Computation'
authors: Tuhin Chakrabarty, Philippe Laban, Chien-sheng Wu
conference: "Arxiv"
year: 2025
bibkey: chakrabarty2025ai
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.07532'}
tags: ['Reinforcement Learning', 'RAG', 'Attention Mechanism', 'Model Architecture']
---
AI-generated text is proliferating across domains, from creative writing and
journalism to marketing content and scientific articles. Models can follow
user-provided instructions to generate coherent and grammatically correct
outputs but in this work, we study a more fundamental question: how do we
evaluate and improve the writing quality of AI-generated text? Writing quality
assessment has received less attention from the community, in part because it
is fundamentally subjective and requires expertise. We first introduce the
Writing Quality Benchmark (WQ) by consolidating five writing-preference
datasets into 4,729 writing quality judgments. Our experiments show that most
of the competitive baselines, including state-of-the-art LLMs that excel at
reasoning tasks, barely outperform random baselines on WQ. We then train
specialized Writing Quality Reward Models (WQRM) of various sizes for writing
quality assessment that demonstrate strong generalization on four
out-of-distribution test sets and 74% accuracy on the WQ benchmark. To further
show WQRM's practical benefits during inference, we leverage additional
test-time compute to generate and rank multiple candidate revisions, allowing
us to select higher-quality outputs from an initial draft. Human evaluation
with 9 experienced writers confirm that WQRM-based selection produces writing
samples preferred by experts 66% overall, and 72.2% when the reward gap is
larger than 1 point. We release our datasets and models to encourage community
engagement with writing quality assessment and development of AI writing
systems better aligned with human preferences.
