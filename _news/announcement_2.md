---
layout: post
title: 57% faster on-device inference on Qualcomm hardware
date: 2025-12-01 16:11:00+0900
inline: false
related_posts: false
---

One of the projects I'm most proud of at OptAI: optimizing small language models (sLM) to run entirely on-device — no internet connection required.

On Qualcomm hardware, we improved the model's text-generation speed by **57%** while keeping **EvalOps accuracy at 96.39%**.

#### How we got there

<ul>
    <li>Designed and implemented an <strong>Auto Mixed Precision</strong> algorithm that searches for the optimal quantization options under a target model-size constraint.</li>
    <li>Built an automated evaluation benchmark tailored to the Qualcomm environment, reflecting hardware-specific characteristics.</li>
    <li>Iterated on the accuracy/latency trade-off until the model ran fast enough for real edge devices.</li>
</ul>

The recurring lesson: on constrained hardware, the win comes from matching the quantization strategy to the device — and from measuring it with a benchmark you actually trust.
