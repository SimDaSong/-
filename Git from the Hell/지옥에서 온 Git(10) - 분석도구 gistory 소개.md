# 지옥에서 온 Git - 분석도구 gistory 소개

* .git 디렉토리에 어떠한 변화가 생기는가?
* gistroy : 웹에서 돌아감. .git에 있는 내용들을 list로 보여주고, 파일이 변경되거나 추가되면 list 중 제일 위쪽으로 올라감 => 내가 내린 명령이 어떠한 파일에 영향을 주는지 알 수 있음.
* gistroy를 이용하기 위해
  1. python 설치
  2. $ sudo pip install  gistroy
     => 안되면 $ sudo pip3 install gistory
  3. .git 이라는 디렉토리가 있는 디렉토리로 cd 명령어를 통해 이동
  4. $ gitory 명령어를 입력한 후 뜨는 숫자를 기억한 뒤, 웹에서 'localhost:숫자' url을 입력