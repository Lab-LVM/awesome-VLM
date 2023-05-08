# Awesome Vision Language Model

## Overview
- [Awesome Vision Language Model](#awesome-vision-language-model)
  - [Overview](#overview)
  - [Contrastive Learning](#contrastive-learning)
  - [PrefixLM](#prefixlm)
  - [Multi-modal Fusing with Cross Attention](#multi-modal-fusing-with-cross-attention)
  - [Masked-Language Modeling / Image-Text Matching](#masked-language-modeling--image-text-matching)
  - [No Training](#no-training)

## Contrastive Learning

Narrow the distance of latent space between the image and text.

-   [CLIP](https://arxiv.org/abs/2103.00020) [📝***Summary***](/../../issues/1)
-   [CoOp](https://arxiv.org/abs/2109.01134) [📝***Summary***](/../../issues/2)
-   [CoCoOp](https://arxiv.org/abs/2203.05557) [📝***Summary***](/../../issues/3)
-   [CLOOB](https://arxiv.org/abs/2110.11316)
-   [ALIGN](https://arxiv.org/abs/2102.05918)
-   [DeCLIP](https://arxiv.org/abs/2110.05208)
-   [LiT](https://arxiv.org/abs/2111.07991)
-   [FLAVA](https://arxiv.org/abs/2112.04482)

## PrefixLM

Unified multi-modal architecture consisting of encoder and decoder. Main tasks are image-conditioned text generation/captioning and VQA.
- [SimVLM](https://arxiv.org/abs/2108.10904)
- [VirTex](https://arxiv.org/abs/2006.06666v3)
- [Frozen](https://arxiv.org/abs/2106.13884)
- [MAPL](https://arxiv.org/abs/2210.07179)
- [ClipCap](https://arxiv.org/abs/2111.09734)
- [Flamingo](https://arxiv.org/abs/2204.14198) [📝***Summary***](/../../issues/4)


## Multi-modal Fusing with Cross Attention
Fuse visual information into a language model decorder using a cross attention mechanism. Main tasks are image captioning and VQA.

- [VisualGPT](https://arxiv.org/abs/2102.10407) [📝***Summary***](/../../issues/5)
- [VC-GPT](https://arxiv.org/abs/2201.12723)
- [Flamingo](https://arxiv.org/abs/2204.14198) [📝***Summary***](/../../issues/4)
- [FIBER](http://arxiv.org/abs/2206.07643)

## Masked-Language Modeling / Image-Text Matching
Combination of MLM and ITM. MLM predicts the masked word by image that annotated more information as bounding box and ITM matches image and caption among many negative captions.

- [VisualBERT](https://arxiv.org/abs/1908.03557)
- [FLAVA](https://arxiv.org/abs/2112.04482)
- [ViLBERT](https://arxiv.org/abs/1908.02265)
- [LXMERT](https://arxiv.org/abs/1908.07490)
- [BridgeTower](https://arxiv.org/abs/2206.08657)
- [Clinical-BERT](https://ojs.aaai.org/index.php/AAAI/article/view/20204) [📝***Summary***](/../../issues/6)

## No Training
Without training, just using pretrained model, make two features into one space.
- [ASIF](https://arxiv.org/abs/2210.01738)
- [MaGiC](https://arxiv.org/abs/2205.02655)
