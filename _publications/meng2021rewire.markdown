---
layout: publication
title: Rewire-then-probe: A Contrastive Recipe For Probing Biomedical Knowledge Of Pre-trained Language Models
authors: Meng Zaiqiao, Liu Fangyu, Shareghi Ehsan, Su Yixuan, Collins Charlotte, Collier Nigel
conference: "Arxiv"
year: 2021
bibkey: meng2021rewire
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08173"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Knowledge probing is crucial for understanding the knowledge transfer mechanism behind the pre-trained language models (PLMs). Despite the growing progress of probing knowledge for PLMs in the general domain specialised areas such as biomedical domain are vastly under-explored. To catalyse the research in this direction we release a well-curated biomedical knowledge probing benchmark MedLAMA which is constructed based on the Unified Medical Language System (UMLS) Metathesaurus. We test a wide spectrum of state-of-the-art PLMs and probing approaches on our benchmark reaching at most 337; of acc@10. While highlighting various sources of domain-specific challenges that amount to this underwhelming performance we illustrate that the underlying PLMs have a higher potential for probing tasks. To achieve this we propose Contrastive-Probe a novel self-supervised contrastive probing approach that adjusts the underlying PLMs without using any probing data. While Contrastive-Probe pushes the acc@10 to 2837; the performance gap still remains notable. Our human expert evaluation suggests that the probing performance of our Contrastive-Probe is still under-estimated as UMLS still does not include the full spectrum of factual knowledge. We hope MedLAMA and Contrastive-Probe facilitate further developments of more suited probing techniques for this domain.
