---
layout: publication
title: 'Guiding Giants: Lightweight Controllers For Weighted Activation Steering In Llms'
authors: Amr Hegazy, Mostafa Elhoushi, Amr Alanwar
conference: "Arxiv"
year: 2025
bibkey: hegazy2025guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20309"}
tags: ['Fine-Tuning', 'Responsible AI', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Controlling undesirable Large Language Model (LLM) behaviors, such as the generation of unsafe content or failing to adhere to safety guidelines, often relies on costly fine-tuning. Activation steering provides an alternative for inference-time control, but existing methods typically lack fine-grained, adaptive mechanisms. We introduce a novel approach using a lightweight, trainable controller network integrated during inference. This controller network observes specific intermediate LLM activations and predicts both a global scaling factor and layer-specific weights. The predicted global scaling factor and layer-specific weights then dynamically modulate the intensity of a steering patch, derived from a pre-computed "refusal direction" vector, applied across the LLM's layers during generation. Trained on activations from both harmful and benign prompts, our controller learns to discriminatively apply nuanced, layer-aware interventions, activating steering primarily for harmful inputs. Experiments using safety benchmarks like ToxicChat & In-The-Wild Jailbreak Prompts demonstrate that our weighted steering controller significantly increases refusal rates compared to the base LLM, achieving targeted behavioral modification without altering the original model parameters. Our experiments with Llama-3.1-8B, Llama-3.2-1B & Mistral-7B show our approach outperforms existing methods, presenting an efficient and adaptive method for fine-grained control over LLM behavior at inference time.
