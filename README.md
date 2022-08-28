# chest_X_ray_images_binary_classification
흉부 X_ray 이진 분류 프로젝트

# Efficient Net
## 베이스라인 모델
- 데이터 증강
- 신경망 모델: efficient-net 사전 훈련 모델 이용
- 옵티마이저: Adam
- 훈련 및 예측

## 성능 개선
- 데이터 증강: 베이스라인과 동일
- 신경망 구조: 앙상블(efficientnet-b1, efficientnet-b2, efficientnet-b3)
- 옵티마이저: Adam W
- 훈련 및 예측

# GooLeNet
## 전처리
- 데이터 증강(flip, 밝기 변화, 이미지 회전)
- 정규화

## 모델링_Train data set
- 가중치 정규화: L2 norm
- 에포크: 120 (얼리스탑핑 적용 | 베스트 에포크: 14)
- fc층 activation func: softmax

![image](https://user-images.githubusercontent.com/94281700/187064750-5d707156-322a-43a8-96ef-18f63de44f33.png)

## 모델 평가_Test data set
![image](https://user-images.githubusercontent.com/94281700/187064530-892335ef-2367-48f4-9dc1-24b828081ba5.png)
![image](https://user-images.githubusercontent.com/94281700/187064534-60d8bea7-4bd9-4de9-8870-d7f6896b53b1.png)
![image](https://user-images.githubusercontent.com/94281700/187064542-a8636d8b-400f-4a64-a8a8-614ed813912d.png)
![image](https://user-images.githubusercontent.com/94281700/187064904-399d442f-1aca-4bdc-a2d0-bef98739c69a.png)



