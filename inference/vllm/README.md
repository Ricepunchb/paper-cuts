# vLLM

vLLM은 현재 LLM inference 및 서빙에서 De Facto Standard로 자리잡은 오픈소스 라이브러리.

Paged Attention을 통해 VRAM utilization을 최대화하여 KV cache를 최적화하여 latency도 최적화.

huggingface에서 모델을 바로 꽃을수도 있고 OpenAI 라이브러리와 호환되어 편리함.


## Reference
- Official Docs: https://docs.vllm.ai/en/latest/
- Paper Link: https://arxiv.org/pdf/2309.06180

## Objective
1. Environment Setup
2. Basic Usage
3. Check Performance
4. OpenAI Compatible Server