# STUDY(Web-Front)
웹 프론트 관련 스터디 (강의 명, 강의 일정, 강의 내용 정리)
# 강의 명
nomadcoders - '바닐라 JS로 크롬 앱 만들기' 

https://nomadcoders.co/javascript-for-beginners/lobby

# 강의 일정
- 09/19(월) ~ 09/25(일)  [#1.0 Welcome ~ # 1.6 Online IDE]
- 09/26(월) ~ 10/02(일)  [ #2.0 First JS Project ~ #2.8 Function part Two]
- 10/03(월) ~ 10/09(일)  [#2.9 Recap ~ #2.16 Recap]
- 10/10(월) ~ 10/16(일)  [#3.0 The Document Object ~ #3.8 CSS in Javascript part Three]
- 10/17(월) ~ 10/23(일)  [#4.0 Input Values ~ #4.7 Super Recap]
- 10/24(월) ~ 10/30(일)  [#5.0 Intervals ~ #5.3 Recap]
- 10/31(월) ~ 11/06(일)  [#6.0 Quotes ~ #7.3 Saving To Dos]
- 11/07(월) ~ 11/13(일)  [#7.4 Loading To Dos part One ~ #8.2 Conclusions]

# 9/26(월) ~ 10/2(일) 
- #2.0

  CSS, J.S 파일은 브라우저에서 여는 것이 아니라 HTML이 CSS와 J.S 파일을 가져오면서, HTML 파일을 브라우저에서 여는 것이다.
  
- #2.1

  J.S는 숫자와 문자라는 두가지 데이터 타입이 있으며 각각에 대해 뭘 해야 하는지 알고 있다.
  
- #2.2

  변수는 값을 저장하거나 유지하는 역할 / 생성 위해 'CONST'사용 (CONST '변수이름' = 'VALUE';)
  
  변수 이름에는 공백이 들어갈 수 없으며 만약 공백이 필요하다면 다음 단어의 첫 문자를 대문자로 작성 (camelCase)
  
- #2.3

  변수 생성 위해 'let'사용 (let '변수이름' = 'VALUE';)
  
  let 과 const의 차이는 const는 값이 바뀔 수 없다는 것이다.
  
- #2.4

  boolean : ture or false / 따옴표를 사용하지 않음 (사용하는 경우 : 로그인 했는가?)
  
  null : 아무것도 없다는 것을 의미 / false랑 다름 / 자연적으로 발생하지 않음
  
  undefined : 값이 없음, 정의되지 않음을 의미
  
- #2.5

  array를 만들기 위해 [] 로 묶으며 각 항목들을 , 로 나열
  
  array의 데이터에 접근하고 싶다면 array를 갖는 변수이름 작성 후 [] 로 얻고 싶은 항목의 번호 넣기
  
  array에 항목을 추가하려면 '변수이름'.push('VALUE')
  
- #2.6

  CONST '변수이름' = { } 를 사용해 개체의 속성 정의 / { } 밖에서 속성을 추가하거나 수정할 수 있음 ('변수이름'.속성 = 속성값)
  
- #2.7

  function은 어떤 코드를 캡슐화해서 실행을 여러번 할 수 있게 함 / function '함수이름' () {}
  
  { } 안에 있는 것이 함수를 실행시킬 때마다 반복됨 / '함수이름'() 로 실행
  
- #2.8

  function 에서 데이터를 받기 위해서는 function 에 있는 ()에 변수를 넣음 / 해당 변수를 {} 속에도 포함시키면 함수 밖 데이터 값을 실행
