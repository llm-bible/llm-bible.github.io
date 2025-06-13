---
layout: publication
title: 'Correlating And Predicting Human Evaluations Of Language Models From Natural Language Processing Benchmarks'
authors: Rylan Schaeffer, Punit Singh Koura, Binh Tang, Ranjan Subramanian, Aaditya K Singh, Todor Mihaylov, Prajjwal Bhargava, Lovish Madaan, Niladri S. Chatterji, Vedanuj Goswami, Sergey Edunov, Dieuwke Hupkes, Sanmi Koyejo, Sharan Narang
conference: "Arxiv"
year: 2025
bibkey: schaeffer2025correlating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18339"}
tags: ['Responsible AI', 'RAG', 'Security', 'Reinforcement Learning']
---
The explosion of high-performing conversational language models (LMs) has
spurred a shift from classic natural language processing (NLP) benchmarks to
expensive, time-consuming and noisy human evaluations - yet the relationship
between these two evaluation strategies remains hazy. In this paper, we conduct
a large-scale study of four Chat Llama 2 models, comparing their performance on
160 standard NLP benchmarks (e.g., MMLU, ARC, BIG-Bench Hard) against extensive
human preferences on more than 11k single-turn and 2k multi-turn dialogues from
over 2k human annotators. Our findings are striking: most NLP benchmarks
strongly correlate with human evaluations, suggesting that cheaper, automated
metrics can serve as surprisingly reliable predictors of human preferences.
Three human evaluations, such as adversarial dishonesty and safety, are
anticorrelated with NLP benchmarks, while two are uncorrelated. Moreover,
through overparameterized linear regressions, we show that NLP scores can
accurately predict human evaluations across different model scales, offering a
path to reduce costly human annotation without sacrificing rigor. Overall, our
results affirm the continued value of classic benchmarks and illuminate how to
harness them to anticipate real-world user satisfaction - pointing to how NLP
benchmarks can be leveraged to meet evaluation needs of our new era of
conversational AI.
