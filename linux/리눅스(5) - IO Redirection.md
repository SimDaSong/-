# 리눅스 - IO Redirection

* IO Redirection

  * I : Input
  * O : Output
  * Redirection : 방향을 바꾼다

* $ ls -l > result.txt : ls -l 명령의 결과가 result.txt 파일 내에 저장됨

* $ ls -al

  * ls : 프로그램(프로세스)
  * -al : 실행될 때 입력되는 입력 값(command line arguments)
  * 프로그램 결과 출력(standard output)
    => 대체로 모니터에 출력되는 결과를 리다이렉션 시킬 수 있음

   

* 유닉스 계열의 시스템에서의 출력

  1. standard output => 리다이렉션 할 때 >(1>) 사용
  2. standard error(내부적으로 오류가 있을 때) => 리다이렉션 할 때 2> 사용

  ※ $ rm rename2.txt 1> result.txt 2> error.log : 실행 결과를 result.txt에, 실행 중 에러가 나면 그 결과를 error.log에 저장



* 유닉스 계열의 시스템에서의 입력 => 어렵지만 실용적이지 X. 따라서 잘 쓰지 X

  1. $ cat hello.txt

  2. $ cat -> hi => 우리가 입력한(standard input) hi를 출력해줌 
     빠져나올 때는 ^d

     => 리다이렉션 시켜서 $ cat < hello.txt 라고 명령할 수 있음 : hello.txt 파일의 내용을 입력으로 받아서 출력시킨다.



* $ head -n1 < linux.txt > one.txt : linux.txt 파일의 첫 번째 행만을 one.txt 파일에 저장



* UNIX 프로그램에서의 I/O

  1. standard input
  2. standard output/error

  => 이러한 흐름을 IO Stream 이라고 함

