---
layout: publication
title: 'Chinese Toxic Language Mitigation Via Sentiment Polarity Consistent Rewrites'
authors: Xintong Wang, Yixiao Liu, Jingheng Pan, Liang Ding, Longyue Wang, Chris Biemann
conference: "Arxiv"
year: 2025
bibkey: wang2025chinese
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15297"}
tags: ['Responsible AI', 'Model Architecture', 'Reinforcement Learning']
---
Detoxifying offensive language while preserving the speaker's original intent is a challenging yet critical goal for improving the quality of online interactions. Although large language models (LLMs) show promise in rewriting toxic content, they often default to overly polite rewrites, distorting the emotional tone and communicative intent. This problem is especially acute in Chinese, where toxicity often arises implicitly through emojis, homophones, or discourse context. We present ToxiRewriteCN, the first Chinese detoxification dataset explicitly designed to preserve sentiment polarity. The dataset comprises 1,556 carefully annotated triplets, each containing a toxic sentence, a sentiment-aligned non-toxic rewrite, and labeled toxic spans. It covers five real-world scenarios: standard expressions, emoji-induced and homophonic toxicity, as well as single-turn and multi-turn dialogues. We evaluate 17 LLMs, including commercial and open-source models with variant architectures, across four dimensions: detoxification accuracy, fluency, content preservation, and sentiment polarity. Results show that while commercial and MoE models perform best overall, all models struggle to balance safety with emotional fidelity in more subtle or context-heavy settings such as emoji, homophone, and dialogue-based inputs. We release ToxiRewriteCN to support future research on controllable, sentiment-aware detoxification for Chinese.
