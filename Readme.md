### **Update history**
- 220514 : vs code에서 git 연동
- 220514 : install jupyter at VS CODE
- 220511 : 파이썬 설치 관련 서치 및 초기 테스트

#### 초기 세팅 관련 히스토리
- 220514 - Git 연동
    - [생활코딩](https://www.youtube.com/playlist?list=PLuHgQVnccGMAQvSVKdXFiOo51HUD8iQQm) 참고
    - 메시지 전송
    
- 220514 - Jupyter 실행안되는 이슈
    1. Python 버전이 너무 높다.
        \
        3.10 -> 3.9로 변경
    2. Bad file descriptor 오류가 발생한다.
        \
        터미널에 다음과 같이 입력한다
        > pip uninstall pyzmq
        \
        > pip install pyzmq==19.0.2
        
        https://lapina.tistory.com/68 참고

- 참고 강의
    - 유튜브 검색 : 파이썬 비주얼스튜디오
    - 참고 유튜버 : 크리애플