---
title: "[2015 ICML] Unsupervised Domain Adaptation by Backpropagation"
categories: ML
use_math : true
---

처음으로 블로그를 시작해보려고 합니다.
제 연구분야와 관련된 논문과 관심있는 논문에 대한 정리로부터 시작해보겠습니다!

첫번째로 다뤄볼 논문은 가장 쉽고 직관적으로 이해할 수 있는 논문을 준비했습니다.
2015년에 열린 ICML에 제출된 Unsupervised Domain Adaptation by Backpropagation이라는 논문입니다.

<img width="935" alt="image" src="https://user-images.githubusercontent.com/39029444/72676131-26b20c00-3ad1-11ea-94e7-6d6408f76975.png">

제안된 archituecture는 3가지 part로 구성되어 있습니다.

1. Shared feature extractor (green)
2. Label predictor (blue)
3. Domain classifier (red)

input x
