#구직 면접 설문지

@버전 1.0
 
##원본(English) 참여자

@bentruyman (http://bentruyman.com/), @roger_raymond (http://twitter.com/iansym), @ajpiano (http://ajpiano.com/), @paul_irish (http://paulirish.com/), @SlexAxton (http://alexsexton.com/), @boazsender (http://boazsender.com/), @miketaylr (http://miketaylr.com/), @vladikoff (http://vladfilippov.com/), @gf3 (http://gf3.ca/), @jon_neal (http://twitter.com/jon_neal), @wookiehangover (http://wookiehangover.com/) and @darcy_clarke (http://darcyclarke.me)

##한글번역 참여자 (Contributors For Korean Version)

EngForDev.com
@nassol(http://engfordev.com) , @rkJun (http://twitter.com/rkjun), @leedaeyeop(이대엽), @sj38.park, @tw shim,
@원강민(http://www.apollocation.co.kr/)

## 일반적인 질문:

* 트위터 사용하시나요? 
	* 트위터를 사용한다면, 트위터에서 누구 팔로우해요?
* 깃헙을 사용하시나요? 
	* 사용하신다면 어떤 리포지터리를 보고계신가요? 
* 어떤 블로그를 구독하고 계신가요? 
* 어떤 버전관리시스템을 사용하시나요? 
* 어떤 개발 환경을 선호하시나요?(운영체제, 텍스트 편집기, 인터넷 브라우저, 기타)
* 웹 페이지를 어떻게 만들었는지 과정을 설명할 수 있나요?
* 우아한 기능저하와 점진적 향상의 차이점을 설명해보세요.
	* “아무도 그런 것은 할 수가 없습니다.” 라고 답한 사람에게는 보너스 점수를 준다.
	* 피쳐 디텍션을 설명할 수 있으면 추가 보너스 포인트
* 시맨틱 HTML 의 의미를 설명해 보세요.
* 최소화 한다는 건 무슨 뜻입니까?
* 사이트 자산을 여러 도메인에서 서비스하는 것이 좋은 이유는 무엇입니까?
	* 브라우저는 특정 도메인의 자원을 한 번에 얼마나 다운로드합니까?
* 특정 디자인에 대해 8개의 스타일시트가 있다면 이것들을 한 사이트로 어떻게 통합하겠습니까?
	* 파일들의 연관성을 찾으세요.
	* 빌드 시스템내 연결되어 돌아가는 게 아니라면, `@import` 는 쓰지 마세요.
* 프로젝트에 투입되었는데, 코드의 들여쓰기에 기존 인력들은 탭을 써 왔고, 당신은 스페이스를 사용해 왔다면, 어떻게 할 건가요? 
	* `:retab! 커맨드에 관한 문제임`
* 간단한 슬라이드쇼 페이지를 작성해 보세요
	* 자바스크립트를 사용하지 않는다면 추가 점수를 줍니다.
* 코드의 성능을 테스트할 때 어떤 도구를 사용하십니까?
* 올해 한 가지 기술을 마스터할 수 있다면 뭘 마스터하시겠습니까?
* 페이지 부하(인지적 부하 시간과 실제 부하 시간)를 줄이는 3가지 방법을 말씀하세요.
* 표준의 중요성을 설명하세요.

## HTML 관련 질문:

* `doctype`이 하는 일은 뭔가요? `doctype`을 몇 개나 댈 수 있나요?
* 스탠더드 모드와 관용(쿼크) 모드간의 차이를 말해 보세요. 
* XHTML 페이지를 운용할 때 발생하는 제약으로는 뭐가 있나요?
	* 페이지를 `application/xhtml+xml`로 운용할 때 발생하는 문제가 있을까요?  
* 다국어로 작성된 컨텐츠를 가지고있는 페이지를 어떻게 보여줄건가요? 
* HTML5에서 XHTML 구문을 사용할 줄 아나요? HTML5에서 XML을 어떻게 사용하나요?
* `data-` attributes를 어디에 쓰면 좋나요?
* HTML4의 content model은 무엇인가요? 그리고 HTML5의 content model하고는 다른가요? 
* HTML5를 개방형 웹 플랫폼으로 생각해봅시다. HTML5의 기본 구성요소는?
* 쿠키, 세션 스토리지(sessionStorage), 로컬 스토리지(locationStorage)의 차이점을 서술하세요.

## 자바스크립트에 관한 질문들

* 어떤 자바스크립트 라이브러리를 사용해 봤나요?
* 자바와 자바스크립트의 차이점은?
* 미정의(`undefined`)와 미선언(`undeclared`) 변수에 대해 설명해보세요.
* 클로저(closure)란 무엇이고 클로저를 왜/언제 사용할까요?
	* 클로저를 생성할 때 즐겨쓰는 패턴은? 아가일(IIFE에만 적용 가능한)
* 익명 함수의 일반적인 쓰임새는?
* 자바스크립트 모듈 패턴에 대해서 설명하세요. 그리고 어떤 경우에 쓰겠는지 얘기하세요.
	* 깔끔한 네임스페이스(clean namespacing)에 관해 언급하면 추가 점수를 준다.
	* 모듈에 네임스페이스가 없다면?
* 코드를 어떻게 정리합니까? (모듈 패턴, 고전적인 상속?)
* 호스트 객체와 네이티브 객체의 차이점은?
* 두 구문의 차이점은?: 
```javascript
function Person(){} var person = Person() var person = new Person()
```
* `.call` 과 `.apply` 의 차이점은? 
* `Function.prototype.bind` 에 대해 설명해 보세요. 
* 언제 코드를 최적화하나요?
* 자바스크립트에서 상속이 어떤 방식으로 작동하는지 설명할 수 있나요?
	* "그건 아무도 설명할 수 없습니다." 라는 답변에 보너스 점수 주기 
	* 설명하려고 시도한다면 추가 점수를 준다.
* 언제 `document.write()` 를 사용하나요?
	* 올바른 답: 1999년 - 이제 미숙한 개발 관행은 뿌리뽑을 때다.
* 기능 탐지(feature detection)와 기능 추론(feature inference), UA 문자열의 차이점은?
* AJAX에 관해 가능한 한 자세하게 설명하시오.
* JSONP의 작동 방식을 설명하시오(그리고 어떻게 JSONP가 진정한 AJAX가 아닌지도).
* 자바스크립트 템플릿을 써본 적이 있습니까? 그렇다면 무엇을 어떻게 쓰셨나요?
* 호이스팅(hoisting)에 관해 설명하시요.
* FOUC가 뭔가요? FOUC를 피하는 방법은?
* 이벤트 버블링에 관해 설명하시오.
* 어트리뷰트(attribute)와 프로퍼티(property)의 차이점은?
* 자바스크립트 객체에 내장된 기능을 확장하는 것이 안 좋은 이유는?
* 내장 기능(built ins)을 확장하는 것이 좋은 이유는? 
* document load 이벤트와 document ready 이벤트의 차이점은?
* `==` 와 `===`의 차이점은?
* 브라우저 창의 URL로 전달된 질의 문자열 매개변수를 가져하는 방법을 설명해 보세요.
* 자바스크립트와 관련된 동일 출처 정책(same-origin policy)에 관해 설명해 보세요.
* 이벤트 위임에 대해 설명해 보세요.
* 자바스크립트의 상속 패턴에 대해 설명해 보세요.
* 아래의 자바스크립트 코드를 작동하게 만드세요: 
```javascript
[1,2,3,4,5].duplicator(); // [1,2,3,4,5,1,2,3,4,5]
```
* 자바스크립트에서의 메모이제이션(memoization, 반복적인 계산을 방지하는) 전략을 설명하시요.
* 삼항문(Tenary statement)을 왜 이렇게 부르고 여기서 “삼항”이라는 단어가 가리키는 의미는?
* 함수에서 인자의 개수(arity)란 뭔가요?

## JS-Code Examples:

```javascript
>~~3.14
```
질문: 위 구문은 어떤 값을 돌려주는가? 
**답: 3** 

```javascript
"i'm a lasagna hog".split("").reverse().join("");
```
질문: 위 구문은 어떤 값을 돌려주는가? 
**답: "goh angasal a m'i"** 

```javascript
( window.foo || ( window.foo = "bar" ) );
```
질문: window.foo의 값은 무엇인가? 
**답: "bar"** 
window.foo의 초기값이 false나 udefined, 또는 0일 경우. 그 밖의 경우에는 기존 값을 유지

```javascript
var foo = "Hello"; (function() { var bar = " World"; alert(foo + bar); })(); alert(foo + bar);
```
질문: 두 alert 문의 결과는?
**답: "Hello World" 와 ReferenceError: bar is not defined** 

## jQuery 관련 질문:

* “메서드 연쇄 호출(chaining)”에 관해 설명하세요.
* `.end()`가 하는 것은 무엇인가요? 
* 이벤트 핸들러를 바인딩할 때 네임스페이스를 지정하는 방법과 그 이유는?
* 효과(또는 fx) 큐란?
* `.get()`, `[]`, 와 `.eq()` 의 차이점은 무엇인가요?? 
* `.bind()`, `.live()`, 와 `.delegate()` 간의 차이는 무엇인가요?
* `$` 와 `$.fn`의 차이점은? 또 `$.fn`은 무엇인가요?
* 다음 셀렉터를 최적화해보세요: 
```javascript
$(".foo div#bar:eq(0)")
```

## CSS 관련 질문:

* CSS의 "리셋(reset)" 이 무엇인지와 장점에 대해 설명하세요.
* Floats에 대해 설명하고, 어떤 방식으로 작동하는지 설명하세요.
* What are the various clearing techniques and which is appropriate for what context? 
* CSS의 sprite 기법을 설명하고, 어떤 방식으로 페이지나 사이트에 구현하는지를 설명하세요.
* IE 박스모델과 W3C 박스 모델의 차이점은 무엇입니까?
* What are your favourite image replacement techniques and which do you use when? 
* CSS 프로퍼티 핵, 조건부 .css 파일 포함시키기, ...그리고 또 뭐가 있나요?
* 기능이 제한되어있는 브라우저에서 어떻게 페이지를 보여줍니까?
	* 사용하는 기술/처리기법은 무엇입니까?
* 화면에 보여주는 컨텐츠를 숨기는 다른 방법들은 무엇입니까? (화면에 보이진 않아도, 화면을 읽어주는 프로그램-음성출력같은-에서는 가능해야함)
* 그리드 시스템을 사용한 경험이 있다면, 어떤 그리드 시스템을 선호합니까?
* Have you used or implement media queries or mobile specific layouts/CSS? 
* Any familiarity with styling SVG? 
* 웹페이지의 인쇄를 최적화하기 위해서는 어떻게 합니까?
* What are some of the "gotchas" for writing efficient CSS? 
* CSS 전처리기를 사용합니까? 
	* If so, describe what you like and dislike about the CSS preprocessors you have used. 
* How would you implement a web design comp that uses non-standard fonts? (avoid mentioning webfonts so they can figure it out) 
* Explain how a browser determines what elements match a CSS selector?  

## Optional fun Questions:

* 지금까지중 가장 멋지게 코딩했던 것은 무엇인지, 그리고 가장 자랑스러웠던 것은?
* HTML5 갱 사인을 아시나요? (역주: 셋과 둘, 또는 넷과 하나를 표시하는 행위)
* Are you now, or have you ever been, on a boat. 
* 파이어버그/웹킷 인스펙터에서 가장 좋아하는 부분을 말해 보세요.
* Do you have any pet projects? What kind? 
* Explain the significance of "cornify". 
* On a piece of paper, write down the letters A B C D E vertically. Now put these in descending order without writing one line of code. 
	* Wait and see if they turn the paper upside down
* This should make the laugh and is a fine way to relieve some tension at the end of the interview.  
* 해적 또는 닌자?
	* Bonus if it's a combo and a good reason was given (+2 for zombie monkey pirate ninjas) 
* 웹 개발이 아니었다면, 무엇을 하고 있었을 것 같습니까?
* Where in the world is Carmen Sandiego? (hint: their answer is always wrong) 
* 자주쓰는 인터넷 익스플로러의 기능은 무엇입니까?
* 이 문장을 완성하세요: Brendan Eich 와 Doug Crockford 는 자바스크립트의 __________ 이다.
* jQuery: 멋진 라이브러리나 최고의 라이브러리가 있다면 의견 주세요.
