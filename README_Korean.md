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
	* 피쳐 디텍션(얼굴 인식 기술인거 같기도..)을 설명할 수 있는 보너스 포인트
* 시맨틱 HTML 의 의미를 설명해 보세요.
* 최소화 한다는 건 무슨 뜻입니까?
* 사이트 자산을 여러 도메인에서 서비스하는 것이 좋은 이유는 무엇입니까?
	* 브라우저는 특정 도메인의 자원을 한 번에 얼마나 다운로드합니까?
* 특정 디자인에 대해 8개의 스타일시트가 있다면 이것들을 한 사이트로 어떻게 통합하겠습니까?
	* Looking for file concatenation.
	* Points off for `@import`, unless it works in conjunction with a build system.  
* If you jumped on a project and they used tabs and you used spaces, what would you do? 
	* `issue :retab! command`
* Write a simple slideshow page 
	* Bonus points if it does not use JS.  
* What tools do you use to test your code's performance? 
* If you could master one technology this year, what would it be? 
* Name 3 ways to decrease page load. (perceived or actual load time) 
* Explain the importance of standards.  

## HTML-Specific Questions:

* What's a `doctype` do, and how many can you name? 
* What's the difference between standards mode and quirks mode? 
* What are the limitations when serving XHTML pages? 
	* Are there any problems with serving pages as `application/xhtml+xml`?  
* How do you serve a page with content in multiple languages? 
* Can you use XHTML syntax in HTML5? How do you use XML in HTML5? 
* What are `data-` attributes good for? 
* What are the content models in HTML4 and are they different in HTML5? 
* Consider HTML5 as an open web platform. What are the building blocks of HTML5? 
* Describe the difference between cookies, sessionStorage and localStorage.  

## JS-Specific Questions

* Which JavaScript libraries have you used? 
* How is JavaScript different from Java? 
* What are `undefined` and `undeclared` variables? 
* What is a closure, and how/why would you use one? 
	* Your favorite pattern used to create them? argyle (Only applicable to IIFEs)  
* What's a typical use case for anonymous functions? 
* Explain the "JavaScript module pattern" and when you'd use it. 
	* Bonus points for mentioning clean namespacing. 
	* What if your modules are namespace-less?  
* how do you organize your code? (module pattern, classical inheritance?) 
* What's the difference between host objects and native objects? 
* Difference between: 
```javascript
function Person(){} var person = Person() var person = new Person()
```
* What's the difference between `.call` and `.apply`? 
* explain `Function.prototype.bind`? 
* When do you optimize your code? 
* Can you explain how inheritance works in JavaScript? 
	* Bonus points for the funny answer: "no one can" 
	* Extra bonus points if they take a stab at explaining it  
* When would you use `document.write()`? 
	* Correct answer: 1999 - time to weed out the junior devs  
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