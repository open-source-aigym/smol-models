# 🧠 SmolModels: Lightweight AI Models for Code, Language, and Vision

Welcome to **SmolModels**, a collection of compact yet capable AI models trained for language, code, and vision-language tasks. Built on the latest open techniques and optimized for performance and efficiency, SmolModels are your go-to for lean AI applications.

## 🔍 Overview

SmolModels include:

* **SmolLLaMA** – A language model fine-tuned with methods inspired by [smollm3](https://huggingface.co/AIGym/smollm3).
* **SmolCoder** – A code-focused model trained using approaches from [opencoder](https://huggingface.co/AIGym/opencoder).
* **SmolLLaVA** – A vision-language model incorporating ideas and methods from [LLaVA](https://huggingface.co/collections/llava).

All models are available on [Hugging Face](https://huggingface.co/AIGym).

## 🏋️‍♂️ Training & Methods

We drew heavily from open training pipelines to guide model development:

| Model     | Inspired By | Description                                                                     |
| --------- | ----------- | ------------------------------------------------------------------------------- |
| SmolLLaMA | `smollm3`   | Efficient language modeling with modern attention and tokenizer improvements    |
| SmolCoder | `opencoder` | Code model trained using high-quality programming datasets and tailored prompts |
| SmolLLaVA | `llava`     | Vision-language training with instruction-tuned multimodal supervision          |

We made adjustments to improve performance at smaller scales and align the models with real-world tasks using domain-specific fine-tuning.

## 📚 Datasets

We trained each model using curated dataset collections on Hugging Face:

* 🦙 **SmolLLaMA**: [smollama-collection](https://huggingface.co/collections/AIGym/smollama-collection-6878e0e9765d17a6539f8730)
* 💻 **SmolCoder**: [smolcoder-collection](https://huggingface.co/collections/AIGym/smolcoder-collection-6880d2165bc0e20b13acacee)
* 🖼️ **SmolLLaVA**: [smollava-collection](https://huggingface.co/collections/AIGym/smollava-collection-687fa6e1f9490fd06d28b7fd)

All datasets are open-source, cleaned, and formatted for optimal model training.

## 🔤 Tokenizer

We use a custom tokenizer based on the **LLaMA 3.1 Chat** template, extended with tokens from:

* `smollm3`
* `llama4`
* `gemma3`

This ensures token compatibility across language, code, and vision tasks.

## 🚀 Usage

Coming soon: inference examples, API integration, and downstream benchmarks.

## 📌 License

All models and datasets follow the licenses of their respective upstream sources. We encourage responsible use.

## 🙌 Acknowledgements

Big thanks to the open-source community for tools, models, and training pipelines that made this project possible — especially:

* [smollm3](https://huggingface.co/AIGym/smollm3)
* [opencoder](https://huggingface.co/AIGym/opencoder)
* [llava](https://github.com/haotian-liu/LLaVA)

---

Feel free to suggest additions or request features via issues or pull requests!
