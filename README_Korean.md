#구직 면접 설문지

@버전 1.0
 
##원본 참여자

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
* 우아한 퇴보와 점진적 개선의 차이점을 설명해보세요.
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
* What's the difference between feature detection, feature inference, and using the UA string 
* Explain AJAX in as much detail as possible 
* Explain how JSONP works (and how it's not really AJAX) 
* Have you ever used JavaScript templating, and if so, what/how? 
* Explain "hoisting". 
* What is FOUC? How do you avoid FOUC? 
* Describe event bubbling. 
* What's the difference between an "attribute" and a "property"? 
* Why is extending built in JavaScript objects not a good idea? 
* Why is extending built ins a good idea? 
* Difference between document load event and document ready event? 
* What is the difference between `==` and `===`? 
* Explain how you would get a query string parameter from the browser window's URL. 
* Explain the same-origin policy with regards to JavaScript. 
* Explain event delegation. 
* Describe inheritance patterns in JavaScript. 
* Make this work: 
```javascript
[1,2,3,4,5].duplicator(); // [1,2,3,4,5,1,2,3,4,5]
```
* Describe a strategy for memoization (avoiding calculation repetition) in JavaScript. 
* Why is it called a Ternary statement, what does the word "Ternary" indicate? 
* What is the arity of a function?  

## JS-Code Examples:

```javascript
>~~3.14
```
Question: What value is returned from the above statement? 
**Answer: 3** 

```javascript
"i'm a lasagna hog".split("").reverse().join("");
```
Question: What value is returned from the above statement? 
**Answer: "goh angasal a m'i"** 

```javascript
( window.foo || ( window.foo = "bar" ) );
```
Question: What is the value of window.foo? 
**Answer: "bar"** 
if intially window.foo was false, undefined or zero else it will retain its value.

```javascript
var foo = "Hello"; (function() { var bar = " World"; alert(foo + bar); })(); alert(foo + bar);
```
Question: What is the outcome of the two alerts above? 
**Answer: "Hello World" & ReferenceError: bar is not defined** 

## jQuery-Specific Questions:

* Explain "chaining". 
* What does `.end()` do? 
* How, and why, would you namespace a bound event handler? 
* What is the effects (or fx) queue? 
* What is the difference between `.get()`, `[]`, and `.eq()`? 
* What is the difference between `.bind()`, `.live()`, and `.delegate()`? 
* What is the difference between `$` and `$.fn`? Or just what is `$.fn`. 
* Optimize this selector: 
```javascript
$(".foo div#bar:eq(0)")
```

## CSS-Specific Questions:

* Describe what a "reset" CSS file does and how it's useful. 
* Describe Floats and how they work. 
* What are the various clearing techniques and which is appropriate for what context? 
* Explain CSS sprites, and how you would implement them on a page or site. 
* What are the differences between the IE box model and the W3C box model? 
* What are your favourite image replacement techniques and which do you use when? 
* CSS property hacks, conditionally included .css files, or... something else? 
* How do you serve your pages for feature-constrained browsers? 
	* What techniques/processes do you use?  
* What are the different ways to visually hide content (and make it available only for screen readers)? 
* Have you ever used a grid system, and if so, what do you prefer? 
* Have you used or implement media queries or mobile specific layouts/CSS? 
* Any familiarity with styling SVG? 
* How do you optimize your webpages for print? 
* What are some of the "gotchas" for writing efficient CSS? 
* CSS 전처리기 (예- LESS 와 같은) 를 사용합니까? 
	* If so, describe what you like and dislike about the CSS preprocessors you have used. 
* How would you implement a web design comp that uses non-standard fonts? (avoid mentioning webfonts so they can figure it out) 
* Explain how a browser determines what elements match a CSS selector?  

## Optional fun Questions:

* What's the coolest thing you've ever coded, what are you most proud of? 
* Do you know the HTML5 gang sign? 
* Are you now, or have you ever been, on a boat. 
* Tell me your favorite parts about Firebug / Webkit Inspector. 
* Do you have any pet projects? What kind? 
* Explain the significance of "cornify". 
* On a piece of paper, write down the letters A B C D E vertically. Now put these in descending order without writing one line of code. 
	* Wait and see if they turn the paper upside down
* This should make the laugh and is a fine way to relieve some tension at the end of the interview.  
* Pirate or Ninja? 
	* Bonus if it's a combo and a good reason was given (+2 for zombie monkey pirate ninjas) 
* If not Web Development what would you be doing? 
* Where in the world is Carmen Sandiego? (hint: their answer is always wrong) 
* 자주쓰는 인터넷 익스플로러의 기능은 무엇입니까?
* 이 문장을 완성하세요: Brendan Eich 와 Doug Crockford 는 자바스크립트의 __________ 이다.
* jQuery: 멋진 라이브러리나 최고의 라이브러리가 있다면 의견 주세요.