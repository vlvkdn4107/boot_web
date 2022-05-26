학습 목표

flexbox에 대해 알아 보자
요즘에는 Grid flex를 사용한다

flex 란
(유연한, 2차원 레이아웃에서 잘 작동한다.)

규칙1
flexbox 자식을 원하는 대로 움직이게 하기 위해서는 기본적으로 부모요소에 명시를 한다
즉, flexbox-container 로 만들어 주면 된다.

규칙2
주측(main axis), 교차축(cross axis)
justify-content, justify(현재 방향에 주축을 담당하는 속성이다.)
align-item (교차축을 담담하는 속성이다.)

기본적으로 추축은 수평이고 교차축은 수직이다
하지만 default 이기 떄문에 변경될 수 있다.

100vh(viewport height) 스크린마다 다르다