# 제품/상품 분류 모델링 프로젝트
## project 설명
  + 제품 데이터(train data)를 입력받아 해당 데이터의 속성(attribute)을 기준으로 분류
  + 분류되는 데이터를 이용하여 Decision 트리 형성
  + 트리의 leaf node에 각 속성에 대한 결과 저장
  + test data가 입력되면, 이미 만들어진 트리로 분류하여 결과 예측
  + input data : 자동차 디자인, 성능, 안전 등에 관한 데이터
  + output data : 위의 속성을 가진 임의의 자동차에 대한 평가
## Tech & Skill
  + Decision Tree Algorithm
  + Python
## 실행 방법
  + python Tree.py dt_train1.txt dt_test1.txt
## 입력 데이터 형식
<img width="681" alt="_2021-05-16__1 52 58" src="https://user-images.githubusercontent.com/83147205/165558910-464fcec0-278c-4112-8d67-98e1769fc31e.png">

## 분류 결과 캡쳐
<img width="789" alt="_2021-05-16__1 54 36" src="https://user-images.githubusercontent.com/83147205/165559029-0da76f71-abfe-4074-8ed9-ae1c68bf65fd.png">
