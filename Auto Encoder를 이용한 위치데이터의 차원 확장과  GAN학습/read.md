
#abstract

Generative Adversial Network(GAN)은 훈련데이터의 확률분포를 학습하는 대표적인 생산적 모델
(Genertive Model)로 여러 분야에 활용되고 있다. 최근 모바일 장치를 이용한 포지셔닝 데이터의 대량수
집이 가능해지면서 GAN을 활용해 위치데이터(위도,경도)를 생산하는 연구가 있었다. 하지만, 훈련 데이터
가 위치데이터와 같이 복잡한 분포를 가지는 저차원 데이터인 경우 GAN의 학습이 불안정해진다는 문제점
이 있다. 본 논문은 기본적인 Auto Encoder(AE)를 이용해 위치데이터의 차원을 확장시키는 방법을 제시
한다. 실험을 통해, 해당 방법으로 차원이 늘어난 데이터를 GAN에 학습시킨다면 학습 안정에 효과가 있
고, 의미있는 학습이 가능하다는 것을 확인하였다.
