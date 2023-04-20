# 🖥️ 프로젝트(개인) 소개
Canvas를 활용한 게임만들기(무단횡단하기 게임)
<br>

## 🕰️ 개발 기간
* 22.12.05 - 22.12.14

## ⚙️ 사용한 스킬
Html, Css, JavaScript

## 📌 주요 기능
### Start
- Enter 누를 시 게임 시작

### 방향키
- a, w, d, s 누를시 캐릭터 위, 아래, 좌, 우 방향 이동 구현

### 라이프, 점수, 메세지
- 라이프(기회)는 3회
- 캐릭터가 건너편까지 도착할 시 +1, 원점 복귀
- 자동차와 충돌하거나 건너편 도착할 시 메세지 출력 

### 장애물(자동차)
- 좌,우 4차선 도로에 자동차 랜덤으로 출력
- 자동차 생성은 왼쪽 도로 함수, 오른쪽 도로 함수 따로 만들어서 생성함
- 자동차 배치는 Math.random()을 사용하여 랜덤으로 생성
- 자동차 화면 밖으로 나갔을 시 splice()를 사용하여 제거하였음
 
### 충돌
- 캐릭터와 자동차 충돌 시 캐릭터 원점으로 복귀, 라이프 -1 감소, 메세지 전달

### 게임종료
- 라이프가 0이 될 경우 게임이 종료와 함께 게임종료창 출력
- Enter 누르면 재시작

### 문제
- 초반에 자동차가 활성화 될때까지 약 2~3초 정도 걸리고 점수 먹기 쉬워서 setTimeOut을 사용하여 5초뒤에 캐릭터 움직이게 설정함
- 배열에 중복값이 들어가서 자동차가 겹쳐서 출력되는 현상 있음 


## 📷 View

<details><summary>게임 이미지</summary>
<img src="https://user-images.githubusercontent.com/111848336/233377592-04722766-07a3-418d-bcd3-170cee0c217e.png" width="700px" height="450px"/>
<div/>
<img src="https://user-images.githubusercontent.com/111848336/233377681-238dc3fc-f3d5-4796-a17d-5827172cc4f5.png" width="700px" height="450px"/>
<div/>
<img src="https://user-images.githubusercontent.com/111848336/233377751-47949542-3a93-4802-901f-b5b3f06eae45.png" width="700px" height="450px"/>
<div/>
<img src="https://user-images.githubusercontent.com/111848336/233377836-b29709d6-17c0-40d1-9e55-9a3bfaa451f9.png" width="700px" height="450px"/>
<div/>
</details>


