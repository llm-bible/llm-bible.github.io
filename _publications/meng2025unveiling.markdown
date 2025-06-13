---
layout: publication
title: 'R.R.: Unveiling LLM Training Privacy Through Recollection And Ranking'
authors: Wenlong Meng, Zhenyuan Guo, Lenan Wu, Chen Gong, Wenyan Liu, Weixian Li, Chengkun Wei, Wenzhi Chen
conference: "Arxiv"
year: 2025
bibkey: meng2025unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12658"}
tags: ['Prompting', 'Security', 'Training Techniques', 'RAG']
---
Large Language Models (LLMs) pose significant privacy risks, potentially
leaking training data due to implicit memorization. Existing privacy attacks
primarily focus on membership inference attacks (MIAs) or data extraction
attacks, but reconstructing specific personally identifiable information (PII)
in LLM's training data remains challenging. In this paper, we propose R.R.
(Recollect and Rank), a novel two-step privacy stealing attack that enables
attackers to reconstruct PII entities from scrubbed training data where the PII
entities have been masked. In the first stage, we introduce a prompt paradigm
named recollection, which instructs the LLM to repeat a masked text but fill in
masks. Then we can use PII identifiers to extract recollected PII candidates.
In the second stage, we design a new criterion to score each PII candidate and
rank them. Motivated by membership inference, we leverage the reference model
as a calibration to our criterion. Experiments across three popular PII
datasets demonstrate that the R.R. achieves better PII identical performance
compared to baselines. These results highlight the vulnerability of LLMs to PII
leakage even when training data has been scrubbed. We release the replicate
package of R.R. at a link.
