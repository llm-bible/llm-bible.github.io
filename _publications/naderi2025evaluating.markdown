---
layout: publication
title: 'Evaluating Prompt Engineering Techniques For Accuracy And Confidence Elicitation In Medical Llms'
authors: Nariman Naderi, Zahra Atf, Peter R Lewis, Aref Mahjoub Far, Seyed Amir Ahmad Safavi-naini, Ali Soroush
conference: "Arxiv"
year: 2025
bibkey: naderi2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00072"}
tags: ['Few-Shot', 'GPT', 'Prompting', 'Model Architecture']
---
This paper investigates how prompt engineering techniques impact both accuracy and confidence elicitation in Large Language Models (LLMs) applied to medical contexts. Using a stratified dataset of Persian board exam questions across multiple specialties, we evaluated five LLMs - GPT-4o, o3-mini, Llama-3.3-70b, Llama-3.1-8b, and DeepSeek-v3 - across 156 configurations. These configurations varied in temperature settings (0.3, 0.7, 1.0), prompt styles (Chain-of-Thought, Few-Shot, Emotional, Expert Mimicry), and confidence scales (1-10, 1-100). We used AUC-ROC, Brier Score, and Expected Calibration Error (ECE) to evaluate alignment between confidence and actual performance. Chain-of-Thought prompts improved accuracy but also led to overconfidence, highlighting the need for calibration. Emotional prompting further inflated confidence, risking poor decisions. Smaller models like Llama-3.1-8b underperformed across all metrics, while proprietary models showed higher accuracy but still lacked calibrated confidence. These results suggest prompt engineering must address both accuracy and uncertainty to be effective in high-stakes medical tasks.
