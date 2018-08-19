# 지옥에서 온 Git - branch 만들기

* $ git branch : 내가 지금 사용하고 있는 branch의 목록들이 나옴
  => master : 기본 branch의 이름(일종의 약속 같은 특별한 이름)
  => branch 명 앞에 * 표시가 된 것이 현재 사용하고 있는 branch

* $ git branch exp : exp라는 branch를 하나 만듦

  * 시험적인 프로젝트를 만들 때 exp_라는 접두사를 붙임

* git checkout exp : 원래의 branch에서 checkout하고 exp라는 branch로 넘어감

* branch를 만들면 '원본의 상태를 그대로 복사한' branch가 만들어짐

* $ git log 명령어의 결과는 현재 내가 어떤 branch를 사용하고 있는지에 따라 결과가 달라질 수 있음

* $ git branch -d : branch를 삭제할 때

* $ git branch -D : 병합하지 않은 branch를 강제 삭제할 때

* $ git check -b exp : exp라는 branch를 생성 & 전환

  