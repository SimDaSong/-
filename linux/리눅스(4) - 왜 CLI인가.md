# 리눅스 - 왜 CLI인가?

* CLI : Comment Line Interface

* 왜 CLI(명령어 제어 방식)을 사용하는가?

  1. GUI 방식이 CLI 방식 보다 컴퓨터 파워를 더 많이 소모

  2. GUI 방식은 많은 노동이 필요
     => 프로그램을 실행 시킬 때, 기다려야 함
     => 순차적인 일을 자동화 시킬 때 불편

     * $ mkdir why;cd why

       => mkdir why와 cd why 명령어를 한 줄에

       

* 파이프라인(pipeline) 기능 : 하나의 명령(프로그램, 프로세스)의 실행 결과를 다른 명령(프로그램, 프로세스)의 입력으로 주는 기능

* grep 명령어 : 많은 정보들 중에서 내가 필요한 내용을 찾는 명령어
  => $ grep 텍스트 파일 : 해당 파일에 해당 텍스트가 포함되어 있는 행만을 화면에 출력
  => $ ls --help | grep sort : ls --help 명령의 결과를 grep sort 명령어의 입력으로 받아 출력

* $ ps aux : 현재 실행되고 있는 프로그램들이 출력됨

  => $ ps aux | grep apache : 현재 실행되고 있는 프로그램의 목록을 grep apache 명령어의 입력으로 받아, 현재 실행되고 있는 프로그램 중 apache에 관한 정보만 받아 올 수 있음