# Fine-Tune DeepSeek & LLaMA: SQL Generator

Fine-tuned DeepSeek-R1 and LLaMA-3.2 large language models (LLMs) using **LoRA** and **PEFT** for efficient memory usage and training of quantized models.  
Built an interactive Gradio interface to generate SQL queries with explanations from database schemas and natural language inputs.

---

## Project Overview

- **Model Fine-Tuning**:  
  Fine-tuned the `DeepSeek-R1` and `LLaMA-3.2` models using [LoRA (Low-Rank Adaptation)](https://arxiv.org/abs/2106.09685) and PEFT strategies on the **Gretel synthetic text-to-SQL dataset** from Hugging Face.
  
- **Efficient Training**:  
  Leveraged model quantization techniques and memory-efficient adapters to fine-tune large models even on limited hardware.

- **Interface Development**:  
  Created a user-friendly **Gradio** application that:
  - Accepts natural language questions and database schema descriptions.
  - Generates corresponding SQL queries.
  - Provides explanations for the generated queries.

- **Evaluation Metrics**:  
  Evaluated model performance based on:
  - **Execution accuracy** (whether the query executes correctly).
  - **Syntax correctness** (whether the query is syntactically valid).

---

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (Parameter-Efficient Fine-Tuning)
- LoRA
- Gradio
- Hugging Face Datasets (Gretel synthetic text-to-SQL)

---
