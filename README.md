# transition_practice

패스트 캠퍼스 front-end 강의 중 전환에 대하여 공부

### transition에 관하여(active)

    - 부여한 요소에 전환효과를 1s 동안 준다
    - 초에 따라 전환효과가 느려지거나 빨라지고 한다
    - 클릭을 하고 있어야지 전환효과가 적용된다.
    
    1초 설정
   ![Hnet com-image](https://user-images.githubusercontent.com/88579497/140448626-33bf8ead-ea0c-496e-9f75-4062fe9cc6d3.gif)

    3초 설정
   ![Hnet com-image (1)](https://user-images.githubusercontent.com/88579497/140448904-c04751b8-5d84-4011-ab06-d5cc49ff97ee.gif)

    
### transition 의 정의

    - 속성명 지속시간 타이밍함수 대기시간
    - 요소의 전환(시작과 끝) 효과를 지정하는 단축 속성
    - 단축 속성에는 trnasition-property, transition-duration, transition-timing-funciton, transition-delay 이 있다.

### transition-property


    - 전환 효과를 사용할 속성 이름을 지정
    - transition : all 이 기본 값으로 active 등으로 지정해둔 css를 다 사용한다
    - 만약 width 1s 를 주면 width 값은 부드럽게 바뀌는 것을 볼 수 있는데 color는 갑자기 바뀌는 것을 볼 수 있다.
    
   ![Hnet com-image (2)](https://user-images.githubusercontent.com/88579497/140449522-31b8b189-8545-4ced-9804-db61a5f2f0d3.gif)



### transiton-duration

    - 기본값 0s
    - transition : .5s (0.5면 0 생략 가능)
    - ex) transition : width 0.5s, background-color 2s 로 여러개의 값을 줄수 있고 width 값은 0.5초 컬러는 2초로 바뀌게 된다.


![Hnet com-image (3)](https://user-images.githubusercontent.com/88579497/140449378-ad567c7c-7b8a-4908-be91-851c0adb1660.gif)

    

### transition-timing-function

    - 전환효과의 타이밍 함수를 지정
    - 기본값 ease = 느리게-빠르게-느리게
    - linear 일정하게
    - ease-in 느리게-빠르게
    - ease-out 빠르게-느리게
    - ease-in-out 느리게-빠르게-느리게
    - ⭐️ 도움이 될 만한 사이트 easing 함수 치트 시트, easing functions mdn, tweenmax easing - 이곳은 참고용

### transition-delay

    - 전환 효과가 몇 초 뒤에 시작할지 대기시간을 지정
    
   ![Hnet com-image (4)](https://user-images.githubusercontent.com/88579497/140449674-2b164247-ddc3-434c-b108-f2fd17e11675.gif)

    
