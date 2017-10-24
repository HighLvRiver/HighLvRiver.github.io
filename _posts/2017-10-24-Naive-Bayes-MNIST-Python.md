---
layout: post
title:  "Naive Bayes From Scratch With MNST dataset Using Python"
date:   2017-10-24 10:00:00
categories: Python ML
---

**Naive Bayes** 알고리즘을 이용해서 손글씨 데이터를 예측해보도록 하겠습니다.

나이브 베이즈(또는 베이지안) 분류(**Naive Bayesian Classification**)은 지도 학습(Supervised Learning)을 사용한 간단한 분류 중 하나입니다. 이 분류는 분류를 위해서 **베이즈 룰(Bayes' Rule)**을 기본적으로 사용하고 있습니다. **베이즈 룰을 사용하는 가장 큰 이유는 조건부 확률을 구할 때 베이즈 룰을 이용 시 더 손쉽게 값을 구하는 경우가 있기 때문입니다.**

쉽게 표현한면, 각각의 데이터들이 주어졌을 때, 해당 데이터가 가리키는 값(라벨)이 A일 확률, B일 확률을 각각 구한 뒤, 가장 확률이 높은 값(라벨)을 채택하는 방식이라고 이해할 수 있습니다.

- 참고
    - http://bcho.tistory.com/1010
    - http://unlimitedpower.tistory.com/entry/NLP-Naive-Bayesian-Classification나이브-베이즈-분류
    - http://jihoonlee.tistory.com/22
    
**[한땀 한땀 코드를 작성하면서, 알고리즘을 이해해보도록 하겠습니다.(ipynb)]**


[한땀 한땀 코드를 작성하면서, 알고리즘을 이해해보도록 하겠습니다.(ipynb)]: https://github.com/HighLvRiver/MachineLearning/blob/master/Naive%20Bayes/Naive_Bayes_from_Scratch_with_MNIST.ipynb