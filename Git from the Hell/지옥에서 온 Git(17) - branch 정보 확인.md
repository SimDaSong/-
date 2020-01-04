# 지옥에서 온 Git - branch 정보 확인

* $ git log --branches : 모든 branch의 log 목록을 확인할 수 있음
* $ git log --branches --decorate : 모든 branch의 log 목록과 각 branch의 가장 최신 commit을 확인할 수 있음
* $ git log --branches --decorate --graph : 모든 brnach의 log 목록, 각 branch의 가장 최신 commit, brach간의 graph를 보여줌
* $ git log --branches --decorate --grach --oneline : branch 간의 graph를 좀 더 간결하게 보여줌
* sourcetree라는 프로그램을 이용하면 branch들을 gui 방식으로 확인할 수 있음
* $ git log master..exp : master라는 branch에는 없고 exp라는 branch에는 있는 것들을 보여줌
  => master와 exp의 위치를 바꾸면 : exp라는 branch에는 없고 master라는 branch에는 있는 것들을 보여줌
* $ git diff master..exp : master라는 branch와 exp라는 branch의 차이점을 보여줌 

