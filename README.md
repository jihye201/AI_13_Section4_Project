# 🌿식물병 예측 프로젝트🌿
### 식물병, 한국에서는 사과 화상병과 같은 박테리아 균으로 인한 피해가 심각함 초기 예측에 도움이 되는 모델을 만들어 보자 

## ✅ 주제 소개
<img width="691" alt="스크린샷 2022-10-27 오후 5 03 11" src="https://user-images.githubusercontent.com/102234250/198226902-2fc38d07-83ad-496e-9335-6b5039a9a1e6.png">
<img width="691" alt="스크린샷 2022-10-27 오후 5 04 18" src="https://user-images.githubusercontent.com/102234250/198227154-cf3b767a-5ffc-450c-bf26-a58fa849a92b.png">

## 딥러닝 모델링 사용
- 데이터 셋 소개
<캐글 데이터 셋>
https://www.kaggle.com/datasets/sadmansakibmahi/plant-disease-expert


- 데이터 전처리 과정
    - ImageDataGenerator
    
- 데이터 모델 소개
    - keras.Sequential()
        - 순차 모델로 쉽게 구현
    - conv2D
    - Maxpooling2D
    - 활성화 함수로 relu 함수 사용
    - 마지막층에는 softmax 사용
    
- 모델 검증 및 성능 확인

## 한계점
- 사전학습모델 미사용 -> 수정 예정 ! 
- 데이터 양이 많아 에폭시 마다 돌아가는 시간이 너무 길었음
- 현실적인 데이터와 다른 잎 사진에서도 예측을 제대로 하는지 확인하지 못함



## 발표 (링크)
https://youtu.be/7bbPi9SEFdA

* 참고 노션 링크: https://www.notion.so/d4a3f0f0f77d46acb64185812178b6da
