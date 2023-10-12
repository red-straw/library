# library

먼저 비주얼스튜디오에서 개발자 명령프롬프트를 킨다.
md cprog로 cprog라는 이름의 디렉토리를 생성하고
cd cprog로 그 디렉토리안으로 들어온다.
notepad mymath.c는 mymath.c라는 이름의 파일을 만들고 notepad로 이를 실행시킨다.
notepad안에 가감승제가 가능한 c언어 코드를 짜넣고 저장하면 cprog파일안에 저장된다.
cl/c mymath.c는 기존 mymath.c를 이용해 obj파일을 만든다.
lib /OUT:mymath.lib mymath.obj는 mymath.lib를 이용하여 lib를 생성한다.
link mymath mymath.lib는 mymath.lib를 이용해서 최종 실행파일은 만든다.
마지막으로 mymath를 치면 실행파일이 실행이 되고 예제의 22, 33을 입력하면 
두 숫자의 덧셈, 뺄셈, 곱셈, 눗셈을 실행하고 그 결과값을 나타내준다.
