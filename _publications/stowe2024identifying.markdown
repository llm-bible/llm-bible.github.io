---
layout: publication
title: 'Identifying Fairness Issues In Automatically Generated Testing Content'
authors: Kevin Stowe, Benny Longwill, Alyssa Francis, Tatsuya Aoyama, Debanjan Ghosh, Swapna Somasundaran
conference: "Arxiv"
year: 2024
bibkey: stowe2024identifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15104"}
tags: ['Training Techniques', 'Fairness', 'Few-Shot', 'Tools', 'Model Architecture', 'Survey Paper', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Prompting', 'Applications']
---
Natural language generation tools are powerful and effective for generating
content. However, language models are known to display bias and fairness
issues, making them impractical to deploy for many use cases. We here focus on
how fairness issues impact automatically generated test content, which can have
stringent requirements to ensure the test measures only what it was intended to
measure. Specifically, we review test content generated for a large-scale
standardized English proficiency test with the goal of identifying content that
only pertains to a certain subset of the test population as well as content
that has the potential to be upsetting or distracting to some test takers.
Issues like these could inadvertently impact a test taker's score and thus
should be avoided. This kind of content does not reflect the more
commonly-acknowledged biases, making it challenging even for modern models that
contain safeguards. We build a dataset of 601 generated texts annotated for
fairness and explore a variety of methods for classification: fine-tuning,
topic-based classification, and prompting, including few-shot and
self-correcting prompts. We find that combining prompt self-correction and
few-shot learning performs best, yielding an F1 score of 0.79 on our held-out
test set, while much smaller BERT- and topic-based models have competitive
performance on out-of-domain data.
