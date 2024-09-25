### International Summer School in Advances in AI

# Large Language Models and How to Instruction Tune Them (in a Sustainable Way)

### **Authors**: [Danilo Croce](https://scholar.google.it/citations?user=dXewdYAAAAAJ&hl=it) 

### Many thanks to: [Claudiu Daniel Hromei](https://scholar.google.it/citations?user=YQRKKFoAAAAJ&hl=it) for supporting the development of (most of the) code

This repository hosts materials from the Lecture held in the [Summer School Andvances in AI 2024](https://sites.google.com/unimib.it/advancesinai-2024/) organized by the [AIxIA](https://aixia.it/). 

The **objective of this lecture** is:

* **Introduce Transformer-based architectures**, including encoding-decoding, encoder-only, and decoder-only structures.
* **Demonstrate fine-tuning of Large Language Models** (LLMs) on diverse datasets in a multi-task framework.
* Utilize [Low-Rank Adaptation](https://arxiv.org/abs/2106.09685) (LoRA) for **sustainable and efficient tuning** on "modest" hardware (e.g., single 16GB RAM GPU).


The repository includes code for fine-tuning a Large Language Model (based on [LLaMA](https://ai.meta.com/blog/large-language-model-llama-meta-ai/)) to solve NLP tasks, such as the ones proposed in [EVALITA 2023](https://www.evalita.it/campaigns/evalita-2023/). 


## Code

### Lab : Fine-tune a LLaMA-based model for all tasks from EVALITA 2023

At the end, this lecture shows how to encode data from different tasks into specific prompts and fine-tune the LLM using [Q-LoRA](https://arxiv.org/abs/2305.14314). The code can be also used in Google Colab using an Nvidia-T4 GPU with 15GB memory.

The code is heavily based on the one used in ExtremITA system participating to EVALITA 2023:

* [ExtremITA Paper](https://ceur-ws.org/Vol-3473/paper13.pdf)
* [ExtremITA Github Code](https://github.com/crux82/ExtremITA)


The overall process is divided in four steps:

* [**Step 1 - Encoding the data**](LAB_1_ADVANCES_IN_AI_2024.ipynb): it shows how to encode data from an EVALITA task to generate prompts for the LLM
* [**Step 2 - Fine-tuning the LLaMA model**](LAB_2_ADVANCES_IN_AI_2024.ipynb): it shows how to fine-tune the LLMS given the prompts 
* [**Step 3 - Inference: generating answers**](LAB_3_ADVANCES_IN_AI_2024.ipynb): it shows how to use the fined-tuned model
* [**Step 4 - Deconding the data**](LAB_4_ADVANCES_IN_AI_2024.ipynb): it shows how to convert the data to be evaluated in the EVALTA challenge

## Slides

The repository also features **slides** ([LINK](advances-in-ai-2024_nlp.pdf)).

## Excercise

An excercise is proposed in the last slides of the [presentation](advances-in-ai-2024_nlp.pdf).

## Contacts

For queries or suggestions, raise an Issue in this repository or email  [croce@info.uniroma2.it](mailto:croce@info.uniroma2.it)


