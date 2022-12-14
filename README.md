# nar-tutorial
[Slides](https://github.com/ictnlp/nar-tutorial/blob/main/slides.pdf) for EMNLP 2022 tutorial "Non-Autoregressive Models for Fast Sequence Generation".

Abstract: The autoregressive mechanism makes it convenient to train sequence generation models, but the generation is slow since autoregressive models can only generate the target sequence word-by-word. Non-autoregressive (NAR) models generate all tokens in parallel by removing the sequential dependencies within the target sequence. While NAR models have received much attention in sequence generation tasks, it is non-trivial for NAR models to obtain satisfactory performance, where the major challenge is to capture the multi-modal data distribution. In this tutorial, we will provide a comprehensive introduction to non-autoregressive sequence generation in four sections. First, we will briefly introduce the background of sequence generation, give the motivation of NAR generation and the multi-modality challenge faced by NAR models. Second, we will introduce efforts to improve NAR generation. We focus on non-autoregressive translation in this paper, which includes many representative methods from different aspects: training objectives, data distillation, latent modeling, upsampling, improved decoding approaches, etc. Third, we will introduce the application of NAR models on a wide range of sequence generation tasks, including language modeling, speech recognition, text-to-speech, etc. Finally, we will conclude this tutorial by summarizing the strengths and challenges of NAR models, and discussing current concerns and future directions of NAR generation.

Presenter: Yang Feng and Chenze Shao
