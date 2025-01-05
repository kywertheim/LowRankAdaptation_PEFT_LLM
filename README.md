# LowRankAdaptation_PEFT_LLM

Context: I completed this guided programming exercise as a part of the Udacity course titled Generative AI Fundamentals.

The code in the Jupyter notebook loads a Hugging Face dataset (imdb movie reviews) and a pretrained Hugging Face model (DistilBERT). It adapts the model for sequence classification by adding a classification head (linear probing) without finetuning at all. Then, the classification head is finetuned with the base model's pretrained weights fixed. Finally, it finetunes the model further by low-rank adaptation, a type of parameter-efficient finetuning.
