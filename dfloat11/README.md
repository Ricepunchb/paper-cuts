# dFloat11
dFloat11은 `Huffman coding`을 통해 bfloat16으로 되있는 모델 가중치를 압축하는 hardward-aware algorithmic design이다.

inference동안 가중치는 GPU 메모리에 압축된 상태로 존재하다가 matmul 직전에 압축을 풀고 연산후에는 즉시 삭제된다.

이 방식을 통해 메모리와 latency를 획기적으로 줄인다.


## Reference
- Official Code: https://github.com/LeanModels/DFloat11
- Paper Link: https://arxiv.org/abs/2504.11651

## Objective
1. Environment Setup
2. Basic Usage
3. Check Performance