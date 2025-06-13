---
layout: publication
title: 'Retention Score: Quantifying Jailbreak Risks For Vision Language Models'
authors: Zaitang Li, Pin-yu Chen, Tsung-yi Ho
conference: "AAAI 2025"
year: 2024
bibkey: li2024retention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17544"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Multimodal Models', 'Tools', 'Merging', 'GPT']
---
The emergence of Vision-Language Models (VLMs) is a significant advancement
in integrating computer vision with Large Language Models (LLMs) to enhance
multi-modal machine learning capabilities. However, this progress has also made
VLMs vulnerable to sophisticated adversarial attacks, raising concerns about
their reliability. The objective of this paper is to assess the resilience of
VLMs against jailbreak attacks that can compromise model safety compliance and
result in harmful outputs. To evaluate a VLM's ability to maintain its
robustness against adversarial input perturbations, we propose a novel metric
called the \textbf\{Retention Score\}. Retention Score is a multi-modal
evaluation metric that includes Retention-I and Retention-T scores for
quantifying jailbreak risks in visual and textual components of VLMs. Our
process involves generating synthetic image-text pairs using a conditional
diffusion model. These pairs are then predicted for toxicity score by a VLM
alongside a toxicity judgment classifier. By calculating the margin in toxicity
scores, we can quantify the robustness of the VLM in an attack-agnostic manner.
Our work has four main contributions. First, we prove that Retention Score can
serve as a certified robustness metric. Second, we demonstrate that most VLMs
with visual components are less robust against jailbreak attacks than the
corresponding plain VLMs. Additionally, we evaluate black-box VLM APIs and find
that the security settings in Google Gemini significantly affect the score and
robustness. Moreover, the robustness of GPT4V is similar to the medium settings
of Gemini. Finally, our approach offers a time-efficient alternative to
existing adversarial attack methods and provides consistent model robustness
rankings when evaluated on VLMs including MiniGPT-4, InstructBLIP, and LLaVA.
