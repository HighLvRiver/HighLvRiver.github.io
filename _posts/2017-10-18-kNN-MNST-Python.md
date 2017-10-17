---
layout: post
title:  "kNN From Scratch With MNST dataset Using Python"
date:   2017-10-18 00:20:00
categories: Python
---

신경망(Neural Network) 알고리즘을 구현해보기에 앞서, 지도학습(supervised learning)에서 활용되는 가장 단순한 종류의 알고리즘인 **kNN**을 이해하고 구현해보도록 하겠습니다.

kNN은 **k-Nearest Neighbors**의 약자이며, 쉽게 설명하면 테스트 데이터가 들어올 경우, 전체 학습 데이터와 신규 테스트 데이터 간의 거리를 구한 뒤, 그 거리가 가까운(인접한) k개의 학습 데이터를 가져와 가장 많이 존재하는 값을 테스트 데이터의 값으로 예측하는 방식을 의미합니다.

- 참고 : http://blog.naver.com/samsjang/220673340574 

이 때 거리를 구하는 방식이 여러 가지가 있을 수 있는데, 일반적으로는 유클리디안 거리를 사용합니다. 유클리디안 거리는 좌표계에 두 점이 있을 때 두 지점의 최단거리(엄밀하게 말하면 유클리디안 좌표계에서 최단거리)를 의미합니다.

실습에 사용할 데이터는 손글씨 데이터(일명 MNIST)이며, 자료는 다음 경로에서 받으실 수 있습니다.

- Sample Dataset 
    - Test Dataset (n=10)
        - https://github.com/makeyourownneuralnetwork/makeyourownneuralnetwork/blob/master/mnist_dataset/mnist_test_10.csv
    - Train Dataset (n=100)
        - https://github.com/makeyourownneuralnetwork/makeyourownneuralnetwork/blob/master/mnist_dataset/mnist_train_100.csv

- Full Dataset
    - Test Dataset
        - https://pjreddie.com/media/files/mnist_train.csv
    - Train Dataset 
        - https://pjreddie.com/media/files/mnist_test.csv

**[그럼 실제로 kNN 알고리즘을 구현해보도록 하겠습니다.(ipynb)]**


[그럼 실제로 kNN 알고리즘을 구현해보도록 하겠습니다.(ipynb)]: https://github.com/HighLvRiver/MachineLearning/blob/master/kNN/python_kNN_from_Scratch_with_MNIST.ipynb
