---
layout: publication
title: 'Understanding LLM Scientific Reasoning Through Promptings And Model''s Explanation On The Answers'
authors: Alice Rueda, Mohammed S. Hassan, Argyrios Perivolaris, Bazen G. Teferra, Reza Samavi, Sirisha Rambhatla, Yuqi Wu, Yanbo Zhang, Bo Cao, Divya Sharma, Sridhar Krishnan Venkat Bhat
conference: "Arxiv"
year: 2025
bibkey: rueda2025understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01482'}
tags: ['Interpretability and Explainability', 'GPT', 'Applications', 'Model Architecture', 'Tools', 'Prompting']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
natural language understanding, reasoning, and problem-solving across various
domains. However, their ability to perform complex, multi-step reasoning
task-essential for applications in science, medicine, and law-remains an area
of active investigation. This paper examines the reasoning capabilities of
contemporary LLMs, analyzing their strengths, limitations, and potential for
improvement. The study uses prompt engineering techniques on the Graduate-Level
GoogleProof Q&A (GPQA) dataset to assess the scientific reasoning of GPT-4o.
Five popular prompt engineering techniques and two tailored promptings were
tested: baseline direct answer (zero-shot), chain-of-thought (CoT), zero-shot
CoT, self-ask, self-consistency, decomposition, and multipath promptings. Our
findings indicate that while LLMs exhibit emergent reasoning abilities, they
often rely on pattern recognition rather than true logical inference, leading
to inconsistencies in complex problem-solving. The results indicated that
self-consistency outperformed the other prompt engineering technique with an
accuracy of 52.99%, followed by direct answer (52.23%). Zero-shot CoT (50%)
outperformed multipath (48.44%), decomposition (47.77%), self-ask (46.88%), and
CoT (43.75%). Self-consistency performed the second worst in explaining the
answers. Simple techniques such as direct answer, CoT, and zero-shot CoT have
the best scientific reasoning. We propose a research agenda aimed at bridging
these gaps by integrating structured reasoning frameworks, hybrid AI
approaches, and human-in-the-loop methodologies. By critically evaluating the
reasoning mechanisms of LLMs, this paper contributes to the ongoing discourse
on the future of artificial general intelligence and the development of more
robust, trustworthy AI systems.
