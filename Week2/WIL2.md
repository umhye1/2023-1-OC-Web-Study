## 2023-1-OC-Web-Study 
### week1 
https://www.notion.so/Week-1-77f9711d77b64ade8e1d002608798aa5?pvs=4

### week2 
https://www.notion.so/Week-2-0eb4e0a15f2943399f0880fb8bc5cadb?pvs=4

add : working directory에 작업한 파일이 있을 경우 add를 통해 staging area(임시 저장된 상태)로 옮길 수 있다.  
commit : commit으로 local repository로 보내줌
push :commit한 이력이 remote repository
로 저장된다.  

/*pull과 fetch의 차이점*/  
pull : remote repository 변경사항을 받아옴  
    변경된 메타데이터 정보를 확인할 뿐만아니라 최신 데이터를 복사해 로컬 git에 가져옴
    다른 환경 / 위치에서 작업할 때 타인이 commit 해서 이력이 변경되었을 경우  
    -> pull 통해서 가져온 후 작업하는 것이 좋음  
fetch : remote repository에 변경사항이 있는지 확인만하고 변경된 데이터를 local git에 실제로 가져오지 않음 
