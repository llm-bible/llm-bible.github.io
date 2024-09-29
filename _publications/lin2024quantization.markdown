---
layout: publication
title: Qserve W4A8KV4 Quantization And System Co45;design For Efficient LLM Serving
authors: Lin Yujun, Tang Haotian, Yang Shang, Zhang Zhekai, Xiao Guangxuan, Gan Chuang, Han Song
conference: "Arxiv"
year: 2024
bibkey: lin2024quantization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.04532"}
  - {name: "Code", url: "https://github.com/mit&#45;han&#45;lab/qserve"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Quantization', 'Tools']
---
Quantization can accelerate large language model (LLM) inference. Going beyond INT8 quantization the research community is actively exploring even lower precision such as INT4. Nonetheless state45;of45;the45;art INT4 quantization techniques only accelerate low45;batch edge LLM inference failing to deliver performance gains in large45;batch cloud45;based LLM serving. We uncover a critical issue existing INT4 quantization methods suffer from significant runtime overhead (2045;9037;) when dequantizing either weights or partial sums on GPUs. To address this challenge we introduce QoQ a W4A8KV4 quantization algorithm with 445;bit weight 845;bit activation and 445;bit KV cache. QoQ stands for quattuor45;octo45;quattuor which represents 445;845;4 in Latin. QoQ is implemented by the QServe inference library that achieves measured speedup. The key insight driving QServe is that the efficiency of LLM serving on GPUs is critically influenced by operations on low45;throughput CUDA cores. Building upon this insight in QoQ algorithm we introduce progressive quantization that can allow low dequantization overhead in W4A8 GEMM. Additionally we develop SmoothAttention to effectively mitigate the accuracy degradation incurred by 445;bit KV quantization. In the QServe system we perform compute45;aware weight reordering and take advantage of register45;level parallelism to reduce dequantization latency. We also make fused attention memory45;bound harnessing the performance gain brought by KV4 quantization. As a result QServe improves the maximum achievable serving throughput of Llama45;345;8B by 1.2x on A100 1.4x on L40S; and Qwen1.545;72B by 2.4x on A100 3.5x on L40S compared to TensorRT45;LLM. Remarkably QServe on L40S GPU can achieve even higher throughput than TensorRT45;LLM on A100. Thus QServe effectively reduces the dollar cost of LLM serving by 3x. Code is available at https://github.com/mit&#45;han&#45;lab/qserve.
