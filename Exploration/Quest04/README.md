# AIFFEL Campus Online Code Peer Review Templete
<<<<<<< patch-1
- 코더 : 안진용
- 리뷰어 : 변종현
=======
- 코더 : 민유경, 안진용, 윤경석
- 리뷰어 : 류지호, 변종현
>>>>>>> main


<aside>
🤔 피어리뷰 템플릿

<<<<<<< patch-1
- [o]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
=======
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
>>>>>>> main
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
<<<<<<< patch-1
        - ![image](https://github.com/user-attachments/assets/1c7dd531-8e33-49a7-9605-1dd5c0348aac)


- [o]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [o]  모델 선정 이유
    - [o]  하이퍼 파라미터 선정 이유
    - [o]  데이터 전처리 이유 또는 방법 설명

- [o]  **3. 체크리스트에 해당하는 항목들을 수행하였나요? (문제 해결)**
    - [o]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - [o]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - [o]  각 실험을 시각화하여 비교하였나요?
    - [o]  모든 실험 결과가 기록되었나요?
=======
        - ![image](https://github.com/user-attachments/assets/a04422a7-3987-40a1-be61-8032323c12ef)
        - ![image](https://github.com/user-attachments/assets/e6cf20b2-98e9-4236-9ee5-741c2e377f83)


- [x]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [x]  모델 선정 이유
    - [x]  하이퍼 파라미터 선정 이유
    - [x]  데이터 전처리 이유 또는 방법 설명

- [x]  **3. 체크리스트에 해당하는 항목들을 수행하였나요? (문제 해결)**
    - [x]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - [x]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - [x]  각 실험을 시각화하여 비교하였나요?
    - [x]  모든 실험 결과가 기록되었나요?

- [x]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [x]  배운 점
    - [x]  아쉬운 점
    - [x]  느낀 점
    - [x]  어려웠던 점
>>>>>>> main

- [o]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [o]  배운 점
    - [o]  아쉬운 점
    - [o]  느낀 점
    - [o]  어려웠던 점

- [x]  **5.  앱으로 구현하였나요?**
    - [ ]  구현된 앱이 잘 동작한다.
    - [o]  모델이 잘 동작한다.
  
</aside>
# 회고(참고 링크 및 코드 개선)
<<<<<<< patch-1
```
# 리뷰어의 회고를 작성합니다.
![image](https://github.com/user-attachments/assets/d43d4d26-4843-456e-80e0-cc35db812620)
정규화를 생성형 ai에게 물어보면 진용님 코드와는 다른 답변을 주었습니다. 그에 반해 진용님은 문제에서 제시한 텍스트를 코드로 반영해 직관적으로
이해할 수 있었던 점이 좋았습니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
=======
다양한 정규화 기법과 레이블 스무딩, 배치 크기 조정 등을 통해 GAN 훈련의 안정성을 크게 향상시키고, 
각 에포크마다 생성된 이미지를 시각화하며 학습 과정을 꼼꼼히 모니터링한 점이 인상적입니다.
손실과 정확도 변화를 직관적으로 파악할 수 있도록 그래프로 일일히 구현해주신 것도 좋았습니다.
>>>>>>> main
