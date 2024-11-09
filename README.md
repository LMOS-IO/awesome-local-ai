# awesome-local-ai
An index of self hosted AI products

## openai compatible inference engines

- [vllm](https://github.com/vllm-project/vllm) production system focused on batching
- [sglang](https://github.com/sgl-project/sglang) production system focused on structured generation and agentic use
- [aphrodite engine](https://github.com/PygmalionAI/aphrodite-engine.git) a fork of vllm with more quantization support 
- [lorax](https://github.com/predibase/lorax) production system focused on dynamic LORAs by predibase 
- [ollama](https://github.com/ollama/ollama) llamacpp wrapper with some extra features, designed for developer laptops
- [koboldcpp](https://github.com/LostRuins/koboldcpp) fork of llamacpp designed for roleplay
- [lmdeploy](https://github.com/InternLM/lmdeploy/blob/main/docs/en/llm/api_server.md) multimodal server by internLM

## LLM inference engines

- [llama.cpp](https://github.com/ggerganov/llama.cpp) lightweight llm runtime for CPU/GPU
- [exllamav2](https://github.com/turboderp/exllamav2) lightweight llm runtime for GPU. fast quantization + supports TP with any number of GPUs
- [mlc-llm](https://github.com/mlc-ai/mlc-llm) optimised llm runtime for many backends. Can run on wasm.
- [TensorRT-llm](https://github.com/NVIDIA/TensorRT-LLM) nvidia's official runtime for their GPUs
- [ctranslate2](https://github.com/OpenNMT/CTranslate2) C based inference engine for many model types
- [hf transformers](https://github.com/huggingface/transformers) not the fastest but supports the most models

## structured generation

- [formatron](https://github.com/Dan-wanna-M/formatron) super fast rust based token constrained generation
- [LMFE](https://github.com/noamgat/lm-format-enforcer) structured gen for batching with beam search
- [outlines](https://github.com/dottxt-ai/outlines?tab=readme-ov-file) structured gen for many backends with json
- [guidance](https://github.com/guidance-ai/guidance) supports interleaved tool calls
