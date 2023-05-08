## WIL 6   
###  : box model과 FLEX box  

- class : 내가 직접 이름을 지어준 어떤 분류를 만들고, 그 분류들이 스타일이 같도록 함  
- type : 특정 html 속성들은 다 이 스타일을 갖도록 지정해줌  

- 스타일 서열: 
    1.  !important
    2.  인라인 스타일
    3.  id 스타일
    4.  클래스 스타일
    5.  타입 스타일  
       
#### 01. box model  

  1. 블록 레벨 요소  
  - 한 줄을 차지하는 박스  
  - 부모 요소 전체 공간 차지
  <br/>
  2. 인라인 레벨 요소
  - 자신만을 감싸는 박스
  - 차지 x
  <br/>

#### 02. FLEX box layout  
- 아이템이 배열될 방향인 '주축'을 정할 수 있음
- 주축(main axis)과 수직한 축 : cross axis
- main axis = column 
- cross axis = row
<br/>
- justify-content : main axis
- align-item : cross axis
 
#### 과제
1.  justify-content: flex-end;       
2.  justify-content:center;
3.  justify-content: space-around;
4.  justify-content: space-between;
5.  align-items: flex-end;
6.  justify-content: center;  
    align-items: center;
7.  justify-content: space-around;  
    align-items: flex-end;
8.  flex-direction: row-reverse;  
9.  flex-direction: column;
10. justify-content:start;  
    flex-direction:row-reverse;
11. flex-direction:column;  
    justify-content: flex-end;
12. flex-direction:column-reverse;  
    justify-content: space-between;
13. flex-direction: row-reverse;  
    justify-content: center;  
    align-items: end;  
18. flex-wrap: wrap;  
19. flex-direction: column;  
    flex-wrap: wrap;
20. flex-flow: column wrap;
    
    