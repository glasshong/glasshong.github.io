---
layout: page
title: "<span data-lang-ko>온디바이스 sLM 최적화</span><span data-lang-en>On-Device sLM Optimization</span>"
description: "<span data-lang-ko>인터넷 연결 없이 스마트폰에서 통화 내용을 요약할 수 있는 소형 언어모델 제작</span><span data-lang-en>Building an on-device small language model that summarizes phone calls without an internet connection</span>"
company: OptAI
badge_color: "#2563eb"
period: "<span data-lang-ko>2025.09 – 2025.12 (4개월)</span><span data-lang-en>Sep 2025 – Dec 2025 (4 months)</span>"
importance: 1
category: work
---

<div data-lang-ko markdown="0">
  <p><strong>OptAI</strong>에서 LG U+와 진행한 Qualcomm향 온디바이스 소형 언어모델 최적화 프로젝트입니다. 인터넷 연결 없이 스마트폰에서 바로 <strong>통화 내용을 요약</strong>하는 모델을 최적화하였습니다. 원본 모델의 정확도를 최대한 유지하면서 추론 속도를 개선하고, 모델 크기를 줄였습니다.</p>

  <p>클라우드로 데이터를 전송할 필요 없이, 디바이스 내에서 바로 요약이 가능하므로, 개인정보 보호에 유리합니다.</p>

  <h4>담당 업무</h4>
  <ul>
    <li><strong>모델 크기 43% 감소, 추론 속도 57% 개선</strong> — Auto Mixed Precision 알고리즘을 설계하여 목표 모델 크기 제약에 맞춰 최적의 양자화 옵션을 자동 탐색하여 모델 크기 감소 및 추론 속도 향상</li>
    <li><strong>정확도 96.39% 유지</strong> — 원본 GPU 모델 대비 EvalOps 정확도 <strong>96.39%</strong>를 유지</li>
    <li><strong>On-Device 모델 평가 벤치마크 구축</strong> — Qualcomm 환경의 하드웨어 특성을 반영한 벤치마크 평가 파이프라인 구축</li>
  </ul>
</div>

<div data-lang-en markdown="0">
  <p>An on-device small language model optimization project carried out at <strong>OptAI</strong> with <strong>LG U+</strong>, targeting <strong>Qualcomm</strong> devices. I optimized a model that <strong>summarizes phone calls</strong> directly on a smartphone without an internet connection, improving inference speed and reducing model size while preserving as much of the original model's accuracy as possible.</p>

  <p>Because summarization runs entirely on-device with no need to send data to the cloud, it is privacy-friendly.</p>

  <h4>What I Did</h4>
  <ul>
    <li><strong>43% smaller model, 57% faster inference</strong> — designed an Auto Mixed Precision algorithm that automatically searches for the optimal quantization options under a target model-size constraint, reducing model size and improving inference speed.</li>
    <li><strong>Retained 96.39% accuracy</strong> — maintained EvalOps accuracy at <strong>96.39%</strong> relative to the original GPU model.</li>
    <li><strong>Built an on-device evaluation benchmark</strong> — a benchmark/evaluation pipeline reflecting the hardware characteristics of the Qualcomm environment.</li>
  </ul>
</div>
