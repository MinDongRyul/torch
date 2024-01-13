## 파이토치

- 페이스북이 초기 루아(Lua) 언어로 개발된 토치(Torch)를 파이썬 버전으로 개발하여 2017년도에 공개
- 초기에 토치(Torch)는 넘파이(Numpy) 라이브러리처럼 과학 연산을 위한 라이브러리로 공개
- 이후 GPU를 이용한 텐서 조작 및 동적 신경망 구축이 가능하도록 딥러닝 프레임워크로 발전 시킴
- 파이썬답게 만들어졌고, 유연하면서도 가속화된 계산 속도를 제공

## 파이토치 모듈 구조

![image](https://github.com/MinDongRyul/torch/assets/101853960/ce2c338e-272d-4772-8e51-8dad2c167a92)

출처: Deep Learning with PyTorch by Eli Stevens Luca Antiga. MEAP Publication. [https://livebook.manning.com/#!/book/deep-learning-with-pytorch/welcome/v-7/](https://colab.research.google.com/corgiredirector?site=https%3A%2F%2Flivebook.manning.com%2F%23%21%2Fbook%2Fdeep-learning-with-pytorch%2Fwelcome%2Fv-7%2F)

## 파이토치의 구성요소

- torch : 메인 네임스페이스, 텐서 등의 다양학 수학 함수가 포함
- torch.autograd : 자동 미분 기능을 제공하는 라이브러리
- torch.nn : 신경망 구축을 위한 데이터 구조나 레이어 등의 라이브러리
- torch.multiprocessing : 병렬처리 기능을 제공하는 라이브러리
- torch.optim : SGD(Stochastic Gradient Descent)를 중심으로 한 파라미터 최적화 알고리즘 제공
- torch.utils : 데이터 조작 등 유틸리티 기능 제공
- torch.onnx : ONNX(Open Neural Network Exchange), 서로 다른 프레임워크 간의 모델을 공유할 때 사용

## 텐서(Tensors)

- 데이터 표현을 위한 기본 구조로 텐서(tensor)를 사용
- 텐서는 데이터를 담기 위한 컨테이너(Container)로서 일반적으로 수치형 데이터를 저장
- 넘파이(Numpy)의 ndarray와 유사
- GPU를 사용한 연산 가속 가능

![image](https://github.com/MinDongRyul/torch/assets/101853960/33c9df47-e4ef-48a7-861e-2cb6752083aa)

### torch 실습 : torch tutorial.ipynb
