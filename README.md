# [인공지능] Mini Project
미니 프로젝트의 목적은 CIFAR-10 image classification을 구현하고,
다양한 형태로 데이터와 라벨을 변화시키며 모델의 성능이 어떻게 달라지는지 실험적으로 분석하는 것입니다.
데이터와 라벨 성질에 따라 어떻게 학습 결과가 변화할까요?
PyTorch를 사용하여 모델을 학습하고 평가해봅시다.

 

Baseline 모델 구현하기

PyTorch를 사용하여 CIFAR-10 classification을 직접 구현

Data, Label 분포를 바꿔보자

실제 label 분포가 변화하는 다양한 조건을 설계하고, 각 조건에서 모델 성능을 평가 (아래 예시 참조)

 

실험 조건 이름	설명
Baseline	CIFAR-10 정답 라벨 그대로 학습
Random Label Shuffle	학습 데이터의 라벨을 완전히 무작위로 섞어서 학습
Label Noise (20%)	학습 데이터 중 20%의 라벨을 무작위로 다른 클래스로 변경
Input Perturbation	같은 라벨을 사용하되 입력 이미지에 강한 변화를 주어보자 (e.g., crop, blur 등)
 

3. 실험 결과 시각화 및 분석

라벨과 데이터 변화에 따른 정확도 및 클래스별 정확도 비교 (다른 metric 비교도 아주 좋음!)

시각화를 통해 독자가 이해하기 쉽도록 해석하기
