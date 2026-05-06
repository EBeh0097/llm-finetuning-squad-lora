# LLM Fine-Tuning with SQuAD and LoRA

Parameter-efficient fine-tuning of a Falcon language model on SQuAD-style question answering using Hugging Face Transformers, PEFT/LoRA, and LangChain inference.

## Why this project matters
This repository demonstrates practical Generative AI engineering skills that recruiters can review quickly: model integration, agent workflows, prompt engineering, data preprocessing, tool use, and reproducible notebook-based experimentation.

## Skills shown
- Hugging Face Transformers model loading and tokenization
- PEFT/LoRA fine-tuning for causal language models
- SQuAD dataset preprocessing for instruction-style QA
- Trainer-based evaluation with loss and perplexity
- LangChain + Hugging Face pipeline integration

## Project structure
```text
.
├── notebooks/
│   └── llm_fine-tuning_with_squad_and_lora.ipynb
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

## Setup
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Environment variables
Create a `.env` file or export the following variables before running the notebook:

```bash
# No API key required for dataset preparation/training. GPU recommended.
```

## How to run
1. Open the notebook in Jupyter, VS Code, or Google Colab.
2. Install dependencies from `requirements.txt`.
3. Add required API keys as environment variables, never directly inside the notebook.
4. Run cells from top to bottom.
