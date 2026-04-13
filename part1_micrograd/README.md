# Part 1 - Micrograd

Andrej Karpathy의 [The spelled-out intro to neural networks and backpropagation: building micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0) 영상을 보며 따라 구현한 실습 노트.

## 내용

- 미분과 기울기(derivative) 개념
- `Value` 클래스 직접 구현 (scalar-valued autograd engine)
- 연산자 오버로딩 (`+`, `*`, `tanh`, `exp`, `**` 등)
- Forward / Backward pass 이해
- Backpropagation 수동 계산 → 자동화
- Chain Rule 적용
- MLP (Multi-Layer Perceptron) 직접 구현 (`Neuron`, `Layer`, `MLP`)
- PyTorch와 결과 비교

## 파일

- `micrograd.ipynb` - 실습 노트북 (주석 및 노트 포함)
