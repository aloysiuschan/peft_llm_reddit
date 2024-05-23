# Parameter-efficient finetuning of LLM on Reddit AMA dataset</h2>
This repository contains two files:
1) reddit_AMA_full_export.csv: This contains the data that we use to fine-tune the LLM. It contains the AMA (Ask Me Anything) Questions and Answers from two popular subreddits (AMA and IAmA). The original file can be found here: https://www.kaggle.com/datasets/isaacstevens/reddit-ama-questions-and-answers-export
2) finetune_llama_v2_on_reddit_AMA_dataset.ipynb: This is the script that we use to process the data and perform parameter-efficient finetuning of the LLM using LoRA (Low Rank Adaptation). It is run on Google Colab using a T4 GPU. Before running the script, please ensure that you have the following:
   - A huggingface account
   - Access to Meta's Llama 2 model (https://huggingface.co/meta-llama/Llama-2-7b-hf)
   - A WandB (Weights and Biases) account (https://wandb.ai/home)

