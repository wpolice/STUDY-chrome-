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
  
# 10/3(월) ~ 10/9(일) 
- #2.9
  
  let은 업데이트 가능, const는 불가능 / 변수에 숫자 문자 boolean null undefined 가능 / 많은 수의 데이터를 가지게 할 때 list사용. list는 업데이트 가능
  
  
- #2.10

  객체 {속성:속성값} / function 함수이름() {반복할 코드}
 
 
- #2.11
 
  console.log 사용없이 function을 통해 결과값 얻기
 
 
- #2.12

  function 밑에 return 넣기. 해당 함수는 return의 value를 넘겨줌
 
 
- #2.13

  prompt를 통한 입력창으로 사용자에게 값을 받음(옛날 방식) / string을 number로 바꾸기 위해 parseInt() 사용
 
 
- #2.14

  isNaN()으로 숫자인지 아닌지 판단 가능 / if(조건) {조건이 참일 때 실행할 코드} else {조건이 거짓일 때 실행할 코드}
 
 
- #2.15

  else 대신 else if 로 조건 추가 / &&로 조건 두가지를 충족시켜야 함을 명시 / ||로 하나만 충족시켜도 됨을 명시 / else는 선택사항
 
 
- #2.16

  else if를 사용할 때 조건이 중첩되지 않는지 확인할 것 / === : 같은가 / !== : 
  
# 10/10(월) ~ 10/16(일) 
- #3.0
  
  HTML과 상호작용 하기 위해 JS 사용 / HTML에서 정보를 가져올 수 도 있고 JS코드에서 해당 항목을 볼 수 있음
  
  
- #3.1
- 
  document로 JS에서 HTML에 접근할 수 있음 / JS는 HTML 요소를 가지고 오지만 HTML 자체를 보여주지 않음 / getElementsByID로 해당 ID 이름을 가진 요소를 보여줌
 
 
- #3.2
 
  getElementsByClassName으로 해당 class 이름을 가진 요소를 보여줌 / queryselector는 요소를 css 방식으로 검색할 수 있지만 하나의 요소만을 반환
  queryselectorAll은 여러개가 있다면 전부다 
 
 
- #3.3

  모든 event를 JS는 listen 할 수 있음 / event를 listen 하기 위해 eventListener 추가 / ex)title.addEventListener("click", 함수) - 클릭했을 때 일어날 일을 위해 함수 정의
 
 
- #3.4

  console.dir을 통해 사용가능한 event를 찾을 수 있음 / mouseenter: 마우스를 올릴 때마다 반응 / mouseleave: 마우스를 뗄 때마다 반응
 
 
- #3.5

  addEventListener(event이름, 함수)를 on event이름 = 함수 로 바꿀 수 있음 / window에서는 resize, copy, offline, online 등의 이벤트가 가능
 
 
- #3.6

  event를 실행하면 실행될 함수에 if-else를 넣어 경우의 수를 만들 수 있음
 
 
- #3.7

  스타일변형은 JS에서 함께하는 것이 아니라 css 파일을 통해 정의 함으로써 코드를 깔끔하게 할 수 있음
  string을 변수에 넣어 코드에 활용하면 이유를 알기 어려운 오류를 줄일 수 있음
  
  
- #3.8

  JS에서 class를 변경하고 싶을 때 classList를 사용하면 class 들의 목록으로 작업할 수 있음, className은 이전에 class를 상관하지 않고 교체함
  toggle은 사용하면 해당 classList에 class가 있는지 확인해서 만약 있다면 제거하고 없다면 
