# AshuGPT — Built from Scratch

A GPT implementation built from scratch while completing the NeetCode ML Course.

Built by Ashish · August 9, 2026

This repository contains my implementations of the core concepts behind modern neural networks and GPTs — starting from gradient descent and backpropagation and progressing to transformers, attention, and text generation.
## Project Structure

```
model/          Attention, Transformer, GPT architecture
  attention.py             Self-attention head
  multi_head_attention.py  Multi-headed attention
  transformer.py           Transformer block
  gpt.py                   GPT model
  normalization.py         Layer normalization
  batch_normalization.py   Batch normalization
  rms_normalization.py     RMS normalization
  embeddings.py            Word embeddings
  positional_encoding.py   Positional encoding
  kv_cache.py              KV-Cache for fast inference
  grouped_query_attention.py  Grouped query attention

data/           Data pipeline
  tokenizer.py                BPE tokenizer
  vocab.py                    Character-level vocabulary
  loader.py                   Batched training data loader
  dataset.py                  GPT dataset preparation
  nlp_preprocessing.py        NLP preprocessing
  tokenizer_utils.py          Tokenization edge cases

train.py        GPT training loop
generate.py     Text generation

foundations/    Neural network primitives built from scratch
  neuron.py, backprop.py, mlp.py, activations.py, loss.py,
  training_loop.py, dead_relu_detector.py, ...
```

## Quick Start

```bash
pip install -r requirements.txt
python train.py
python generate.py
```

## Course

Built while completing the [NeetCode ML Course](https://neetcode.io/practice?tab=coreSkills&topic=Machine+Learning).

## About

**AshuGPT** is my hands-on implementation of the concepts behind GPT, built progressively from the fundamentals up.

