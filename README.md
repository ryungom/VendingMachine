# 🥤VendingMachine_making
<center>![완성페이지](https://github.com/ryungom/VendingMachine/blob/main/images/view.gif)</center>
<center> - [완성페이지 보러가기](https://ryungom.github.io/VendingMachine/)</center>

## ⚙️issue list
- 22.04.13
  - html,css를 이용하여 최대한 비슷하게 완성. 그러나 딱 한군데, 보라색 콜라위에 검은 배경으로 투명도 80정도로 '품절'로고 띄우기 실패.
  - z-index를 사용하면 될것같긴한데... 안먹힌다
- 22.04.19
  - 보라색 콜라 위 검은 배경으로 '품절'로고 띄우기 성공. 원인은 가상요소에 content:'';을 넣어주지 않아서, 컨텐츠가 없는것으로 인식.
  - 전체 큰 레이아웃들의 height요소를 제거하고 자식요소들이 있는만큼 높이를 생성할 수 있도록 하였다.
  - 가상클래스의 상위 요소에 위치의 근본이 되는 position:relative;를 넣어주고, 해당요소에 position:absolute;를 넣고 z-index를 넣어서 완전히 띄웠다.
    - 그런고로, 품절요소 나타내기 성공!👏
  - 반응형 미디어 쿼리 요소 넣기 성공!! 전체를 감싸는 main에 flex를 넣고 방향을 column, 요소 정렬을 center을 주어 748px(전체 width)보다 화면이 줄어들면 아래방향으로 display가 출력 되도록 수정하였다.
  - 왼쪽요소(.list)와 오른쪽요소(.result)의 float을 none으로 주어 노멀flow에 그대로 안착되어 상위요소인 main이 flex로 하위요소들을 컨트롤 할 수 있도록 바꾸었다.
  - 얼추 피드백을 받은 후, JS요소를 추가하여 진정한 vendingMachine이 될 수 있도록 조정해봐야 할듯 하다.
  - class명 작명을 아직 엄두도 내지 못하였다. 보다 직관적인 class명이 될 수 있도록 진행하기.
