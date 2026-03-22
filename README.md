# Instruction-finetuning-and-ZeroShot-Tweet-Stance-Detection-Using-FLAN-T5-Base
This project explores zero-shot tweet stance detection using the FLAN-T5-Base model, an instruction-tuned transformer. Without any task-specific fine-tuning, the model classifies tweets into Favor, Against, and Neutral categories using carefully designed prompts. The study evaluates different prompting techniques and decoding strategies (Greedy & Beam Search) across multiple benchmark datasets, demonstrating that even lightweight models can achieve meaningful performance in resource-constrained environments.
This project focuses on detecting the stance of tweets toward specific targets using a zero-shot learning approach. Instead of training on labeled data, we leverage the FLAN-T5-Base model with instruction-based prompting to classify tweets into:

FAVOR
AGAINST
NEUTRAL

The goal is to evaluate how effectively a lightweight transformer model performs in real-world NLP tasks without fine-tuning.
