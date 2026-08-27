# LLM Benchmarking Playground: vLLM vs. Ollama Across Industry Harnesses

This notebook serves as a hands-on learning environment for benchmarking Large Language Models using local inference servers and popular evaluation frameworks. It explores performance, accuracy, and agentic capability through four distinct benchmarking pipelines:

* **lm-evaluation-harness (via vLLM):** Evaluates academic task accuracy (e.g., HellaSwag) using a high-throughput OpenAI-compatible API backend.
* **EvalPlus (via vLLM):** Rigorously tests code-generation correctness and strict functional pass rates (e.g., HumanEval) via local model serving.
* **Custom Benchmarking (via vLLM):** Implements personalized, domain-specific evaluation scripts targeting custom datasets and latency metrics.
* **Harbor (via Ollama):** Tests agentic workflows and terminal-based task execution capabilities using Ollama's lightweight local runner.
