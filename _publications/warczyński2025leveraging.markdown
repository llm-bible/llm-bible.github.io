---
layout: publication
title: 'Leveraging Large Language Models For Building Interpretable Rule-based Data-to-text Systems'
authors: Jędrzej Warczyński, Mateusz Lango, Ondrej Dusek
conference: "Arxiv"
year: 2025
bibkey: warczyński2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20609"}
tags: ['Prompting', 'RAG']
---
We introduce a simple approach that uses a large language model (LLM) to
automatically implement a fully interpretable rule-based data-to-text system in
pure Python. Experimental evaluation on the WebNLG dataset showed that such a
constructed system produces text of better quality (according to the BLEU and
BLEURT metrics) than the same LLM prompted to directly produce outputs, and
produces fewer hallucinations than a BART language model fine-tuned on the same
data. Furthermore, at runtime, the approach generates text in a fraction of the
processing time required by neural approaches, using only a single CPU
