---
title: "Attention Is All You Need"
authors: ["Vaswani, Ashish", "Shazeer, Noam", "Parmar, Niki", "..."]
venue: "NeurIPS"
year: 2017
doi: "10.48550/arXiv.1706.03762"
pdf: "https://arxiv.org/abs/1706.03762"
tags: ["LLM", "Transformers"]
status: "reading"
---

# Attention Is All You Need

## 1. Summary
Introduces the Transformer architecture, replacing RNNs with attention-only mechanisms. Key idea: self-attention can capture dependencies without recurrence or convolutions.

## 2. Key Contributions
- Pure attention-based architecture
- Scales well with parallelization
- Outperforms RNNs on translation tasks

## 3. Methods
- Multi-head self-attention
- Positional encoding
- Encoder–decoder structure

## 4. Results
- BLEU score improvements on WMT translation
- Faster training due to parallelism
- Limitations: quadratic complexity with sequence length

## 5. Your Thoughts
- Sparked the LLM revolution
- Connection to your HySon work: foundation for GenAI models
