# Gen AI with LLM: Summarization and Detoxification

This project explores the fine-tuning of large language models (LLMs) for **dialogue summarization** and **output detoxification**. It demonstrates how prompt engineering and model adaptation can significantly improve the quality and safety of generated text.

## 🚀 Project Goals

- Use LLMs (FLAN-T5) to generate concise summaries from real-world dialogues.
- Fine-tune models on custom datasets to reduce toxicity and ensure responsible AI output.
- Compare zero-shot, one-shot, and few-shot learning techniques.
- Evaluate performance improvements using safety and quality metrics.

## 🧠 Techniques Used

- **Prompt Engineering**: Structured zero-, one-, and few-shot prompts for summarization.
- **Transfer Learning**: Fine-tuning FLAN-T5 using Hugging Face Transformers.
- **Safety Tuning**: Custom fine-tuning for detoxification using curated summaries.
- **Evaluation**: ROUGE scores, toxicity classification, and output inspection.

## 🧰 Tools & Libraries

- Python, PyTorch, TensorFlow
- Hugging Face Transformers, Datasets, PEFT
- Evaluate, ROUGE, Detoxify

## 📁 Project Structure

- `1_Summarize_dialogue.ipynb`: Summarizes dialogues using pre-trained LLMs and prompt variants.
- `2_Fne_tune_generative_ai_model.ipynb`: Fine-tunes a generative model on summarization tasks.
- `3_Fine_tune_model_to_detoxify_summaries.ipynb`: Detoxifies generated outputs through additional fine-tuning.

## 📊 Dataset

- [DialogSum Dataset](https://huggingface.co/datasets/knkarthick/dialogsum): ~10K dialogue-summary pairs.
- Custom detoxification dataset: ~3K samples for safe output fine-tuning.

## ✅ Results

- Achieved high-quality summaries through few-shot prompting.
- Fine-tuning improved summarization consistency and relevance.
- Detoxification reduced toxicity scores by over **25%**.

## 💡 Future Work

- Integrate with model deployment tools (e.g., SageMaker, MLflow).
- Expand detoxification to cover more nuanced language issues.
- Add model card and demo using Gradio or Streamlit.

## 📬 Contact

Created by **Nasrin Altafi**  
Feel free to reach out via [GitHub](https://github.com/AltafiNasrin) or [LinkedIn](https://www.linkedin.com/in/nasrin-altafi/)
