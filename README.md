과제 5: 정확도 차이 설명 (Task 5 Explanation)
1. 결과 비교 (Comparison): epochs=2일 때보다 epochs=5일 때의 정확도(Accuracy)가 더 높게 나타났습니다.

2. 이유 (Reason): 이러한 차이가 발생하는 이유는 모델의 반복 학습 때문입니다.

학습 과정: 에포크(Epoch)가 증가한다는 것은 모델이 전체 훈련 데이터를 더 여러 번 반복해서 보았다는 의미입니다.

최적화 (Optimization): 학습이 진행될수록 최적화 함수(SGD)가 경사 하강법(Gradient Descent)을 통해 오차(Loss)를 최소화하는 방향으로 모델의 **가중치(Weight)**를 지속적으로 업데이트합니다.

결론: 따라서 모델이 데이터를 2번 학습했을 때보다 5번 학습했을 때 데이터의 특징을 더 잘 파악하게 되어 분류 정확도가 향상된 것입니다.# Colab_MNIST_Homework
