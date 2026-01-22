# llm_compressor

llm compressor는 vLLM 안에 내장된 라이브러리로 모델 경량화를 담당한다.

## Key features
1. Weight, Activation Quantization
    - Supported Algorithms: `GPTQ`, `AWQ`, `RTN`, `SmoothQuant`
    - Supported Formats: `INT W8A8`, `FP W8A8`
2. Weight only Quantization
    - Supported Algorithms: `GPTQ`, `AWQ`, `RTN`
    - Supported Formats: `INT W4A16`, `INT W8A16`
3. Weight Pruning
    - Supported Algorithms: `SparseGPT`, `Magnitude`, `Sparse Finetuning`
    - Supported Formats: `2:4 (semi-structured)`, `unstructured`

## Reference
- Official Docs: https://docs.vllm.ai/projects/llm-compressor/en/0.8.1/

## Objective
1. Environment Setup
2. Basic Usage
    - Quantization
    - Pruning
3. vLLM compatible check