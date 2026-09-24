# MLOps & LLMOps Interview Guide

Deploying, serving, evaluating, and monitoring machine learning models and LLMs in production.

## Key Topics to Cover

- **Inference & Serving**: vLLM, Ollama, Triton Inference Server, TGI (Text Generation Inference), PagedAttention, KV Caching, Continuous batching.
- **Model Optimization**: Quantization (AWQ, GPTQ, GGUF, INT8/INT4), Pruning, Knowledge Distillation.
- **Fine-Tuning Techniques**: PEFT, LoRA, QLoRA, Full fine-tuning, SFT (Supervised Fine-Tuning), RLHF vs DPO vs ORPO.
- **Evaluation (LLM Evals)**: Ragas (Faithfulness, Answer Relevance, Context Recall), TruLens, DeepEval, LLM-as-a-judge patterns.
- **Guardrails & Safety**: NeMo Guardrails, Llama Guard, PII masking, Output validation, Prompt injection detection.
- **Observability & Tracing**: LangSmith, Phoenix (Arize), OpenInference, Helicone, Token cost tracking, Latency monitoring (TTFT - Time To First Token, TPOT - Time Per Output Token).
