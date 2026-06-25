# safe_nest
Designed and built SAFE-NEST, a six-stage, model-agnostic inference-time safety pipeline (preprocessing → intent classification → generation → response verification → safety gating → iterative refinement) that wraps any open-source LLM without modifying weights, deployed across 6 generator models (from Ollama) on a single RTX 4090.
