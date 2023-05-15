## WIL 7
###  클론 코딩 - 유튜브 html

클론코딩 - 유튜브 html을 만드는 법을 배움   

1. 구획을 나누고, 이를 어떻게 구현할 것인지 계획하는 것이 가장 중요하다.  
  
- 특히 이번 유튜브 html 클론 코딩시에는 크게 8부분으로 나눴음  
  1. 헤더 : header  
  2. 헤더 외 아래 부분 : container  
  3. container 안에서 메인이 되는 부분 : main-container  
  4. 사이드 부분 : aside-container  
  5. 영상 재생부 : video-container  
  6. 영상 게시자 정보 : video-info-container  
  7. 영상 댓글 : comment-container  
     
-> 이를 flex를 이용해 어떻게 배치할지 분석해봐야함  

  1. view(전체) : view 안에 header와 container가 flex-direction :column방향으로 배치되어있음  
  2. header : header 안에 각종 버튼들이 row 방향으로 배치되어있음   
  3. container안에 main-container 와 aside-container가 row 방향으로 배치  
  4. main-container안에는 3개의 container가 columns 방향으로 배치  
  5. video-info-container 안에는 video의 제목, 게시자 정보 등이 columns 방향으로 배치  
  6. comment-container안에 댓글들이 columns 방향으로 배치  
   
2. css 초기화 - 필수는 아님  
   
3.  기본 index 틀을 이용해 만들기  
     
4.  이후 각 구획 따라 만들기  
  

---
  
과제시 어려웠던 부분
  내 컴퓨터의 브라우저에서 화면이 잘 맞지 않았음 -> width / font-size 변경으로 해결  
  

