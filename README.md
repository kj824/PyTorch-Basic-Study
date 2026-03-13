# PyTorch-Basic-Study
PyTorch의 공식 튜토리얼을 바탕으로 기초 파이프라인을 학습한 기록입니다.
외부 강의 없이 공식 문서와 AI 도구를 활용하여 독학으로 진행되었습니다.

## 학습 방법
- 공식 가이드: [Pytorch Quichstart Tutorial](https://docs.pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html)
- AI 도구: Google Gemini
    - 코드의 기술적 의미 해석 및 주석 작성 도움
    - 모델의 손실값(loss) 및 정확도(accuracy) 분석 보조
    - 이론 및 원리(예: 순전파/역전파의 원리, 가중치와 기울기의 상관관계 등)의 정확한 개념 숙지
    - 특정 메서드(예: `.item()`, `.eval()`)의 기술적 명세 및 내부 동작 원리 파악

## 학습 결과
- 데이터셋: Fashion-MNIST
- 최종 정확도: 71.0%
- 인사이트: 상의(Shirt, Coat) 및 신발(Sneaker, Sandal)간의 변별력 보완이 필요

## 사용 기술
- PyTorch
- Google Colab
