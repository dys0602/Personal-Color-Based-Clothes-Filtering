# Personal-Color-Based-Clothes-Filtering-Web

아직 구현중이며 아래 내용은 추후 추가될 예정이므로, 관련 자료는 ```Personal-Color-Based-Clothes-Filtering-Web-Presentation.pdf```를 참고하기를 바란다.

## 1. 문제 인식
많은 의류 추천 시스템은 협업필터링을 통해 사용자의 관심을 반영하거나 가격, 종류 등의 의류 자체에 대한 일반적인 필터링 기능을 제공하지만, 관심도 외에 사용자 개인의 특성을 고려한 추천은 찾아보기 어렵다. 의류를 고르는 기준이 되는 요인 중, 색상이 큰 부분을 차지하므로 개인 소비자에게 어울리는 색의 옷을 판별하여 추천하는 웹 서비스를 떠올렸다. 따라서, 웹에서 진행한 개인의 퍼스널 컬러 판별 결과를 토대로 퍼스널 컬러의 4가지 종류에 따라 옷의 색상을 필터링하여 보여줄 수 있는 웹을 구현한다. 


## 2. 데이터 수집
- 채널 : 무신사
- 항목 : 상의 8개(후드티, 티셔츠 등)별 약 6,000개 수집


## 3. 예상 UI
<img width="600" alt="스크린샷 2022-02-02 오전 5 08 46" src="https://user-images.githubusercontent.com/78864775/152043682-3a92279c-491a-4901-a753-890d4dfb53e9.png">
<img width="600" alt="스크린샷 2022-02-02 오전 5 09 42" src="https://user-images.githubusercontent.com/78864775/152043699-0d81a306-4fbb-4a50-a5eb-ad4b4e91ae1c.png">


## 4. 사용 기술
- Python : opencv, numpy, dlib, BeautifulSoup 등
- Django
- MySQL


## 5. 팀원
|이름|역할|email|
|---|---|---|
|지다영|- 데이터 수집 및 관리 <br> - 프론트엔드/백엔드|dys621124@gmail.com|
|강유정|-|-|
|임채원|-|-|


© 2022 DaYeong Ji <dys621124@gmail.com>
