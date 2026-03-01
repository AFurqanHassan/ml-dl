# Module 5: Large Language Models (LLMs) & Generative AI

The cutting edge of AI. Learn how to work with massive models locally, engineer effective prompts, build RAG systems, fine-tune models for your domain, and create intelligent chatbots.

## Notebooks:

1. **[LLM Basics & Foundations](./llm_basics_intro.ipynb)**: What LLMs are, how they work (tokens, context windows, temperature), training vs inference, quantization, and the open-source model landscape.
2. **[Local LLM Setup (Ollama)](./local_llm_setup.ipynb)**: Step-by-step guide to running models locally — installation, model management, hardware tips, GPU check, and benchmarking.
3. **[LLM Inference with Python](./llm_inference_python.ipynb)**: Programmatic LLM interaction — `generate()` vs `chat()`, streaming, JSON output, multi-turn conversations, error handling, and batch processing.
4. **[Prompt Engineering Guide](./prompt_engineering_guide.ipynb)**: Zero-shot, Few-shot, Chain-of-Thought prompting, system prompts, output guardrails, and prompt structuring best practices.
5. **[Local LLMs with HuggingFace](./huggingface_local.ipynb)**: The industry-standard `transformers` library — Pipeline API, manual tokenizer+model workflows, generation parameters, and model caching.
6. **[RAG Basics with Ollama](./rag_basics_ollama.ipynb)**: Build a Retrieval-Augmented Generation system from scratch — embeddings, cosine similarity, top-k retrieval, text chunking, and the full pipeline.
7. **[Fine-Tuning with LoRA](./fine_tuning_lora.ipynb)**: Parameter-efficient fine-tuning using LoRA/QLoRA — adapter configuration, training loop, before/after comparison, and saving/loading adapters.
8. **[Building a Chatbot with Memory](./chatbot_with_memory.ipynb)**: Multi-turn chatbot — conversation history, streaming responses, context window management, and personality presets.

## Topics Covered:

- Modern Transformer Architectures & LLM Evolution (Encoder vs Decoder models)
- Tokens, Context Windows, Temperature/Top-P, and Quantization (GGUF, GPTQ)
- Training vs Inference, Pre-training vs Fine-tuning, RLHF/DPO alignment
- Prompt Engineering: Zero-shot, Few-shot, Chain-of-Thought, System Prompts
- RAG (Retrieval-Augmented Generation) with embeddings and similarity search
- Fine-Tuning with LoRA/QLoRA using HuggingFace PEFT
- Working with local LLMs (Ollama vs HuggingFace Transformers)
- Building chatbots with memory and context management
