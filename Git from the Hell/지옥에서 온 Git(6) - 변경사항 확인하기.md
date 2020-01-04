# 지옥에서 온 Git - 변경사항 확인하기

* $ git log -p : 각각의 commit과 commit 사이의 소스상 차이점을 확인 가능
  +: 최근의 commit
  -: 이전의 commit
* 각각의 commit은 고유한 id를 가짐
* 두 commit의 내용 상의 차이점을 알고 싶을 때 :
  $ git diff commit1의id..commit2의id
* 변경사항 확인의 장점 : commit 하기 전에 본인의 소스코드에 실수한 것이 있는지 없는지 마지막으로 확인할 수 있는 기회가 주어짐
* $ git diff : 현재 작성 코드와 이전의 코드와의 차이점을 보여줌 => q로 나옴