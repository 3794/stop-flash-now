# Stop Flash Now
## 플래시를 없애자!

Adobe는 2020년 말에 Flash Player를 업데이트 하고 배포하는것을 중단하기로 하였습니다. 크롬은 2020년 12월에 플래시를 크롬에서 제거하기로 하였습니다. 2020년 까지 관련 뉴스를 정리하고, 플래시를 대체하는 기술들에 대해 소개합니다.

## News
* Microsoft IE 10 이하 지원 중단   
https://www.microsoft.com/ko-kr/windowsforbusiness/end-of-ie-support
   >  2016년 1월 12일 이후로 Microsoft는 이전 버전의 Internet Explorer에 대한 보안 업데이트나 기술 지원을 전혀 제공하지 않을 것입니다. 악성 코드가 악용할 수 있는 보안 취약점을 차단하고 사용자와 데이터를 보다 안전하게 보호하려면 보안 업데이트가 반드시 필요합니다.

* Adobe flash 지원 중단   
https://theblog.adobe.com/adobe-flash-update/
   > 특히 2020 년 말에 Flash Player를 업데이트하고 배포하는 것을 중단하고 기존의 Flash는 오픈 웹 포멧으로 마이그레이션하도록 권장 할 것입니다.

* Chrome Flash 제거 계획   
https://www.blog.google/products/chrome/saying-goodbye-flash-chrome/
   >  결국 기본적으로 사용 중지하도록 설정하여 향후 몇 년 동안 플래시를 단계적으로 중단합니다.

* Chromium 플래시 로드멥   
https://www.chromium.org/flash-roadmap

* Microsoft Edge, IE Flash 제거 계획   
https://blogs.windows.com/msedgedev/2017/07/25/flash-on-windows-timeline/
   > 2019 년 중후반에 Microsoft Edge와 Internet Explorer에서 기본적으로 Flash가 비활성화됩니다. 사용자는 두 브라우저 모두에서 Flash를 다시 활성화 할 수 있습니다. 다시 활성화되면 Microsoft Edge는 사이트별로 플래시에 대한 승인을 계속 요구할 것입니다.

* 2018년 네이버지도 베타에서 로드뷰 플래시 제거, WebGL 방식으로 변경   
https://beta.map.naver.com   
https://naver.github.io/egjs-view360/panoviewer.html   

* 7월쯤 배포될 예정인 Chrome 76 부터는 경고문구 계속 노출   
https://9to5google.com/2019/03/22/chrome-warn-flash-player-deprecation-july/
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/chrome-flash-deprecation-warning.png"></img>




## 2D

### 1. CSS 2D Transforms
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie9 이상|
|Others           |ok   |

* mdn css transform   
https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Transforms/Using_CSS_transforms
* codingfactory 2D 확대 또는 축소하기   
https://www.codingfactory.net/10939
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/css-animation-transform-scale-01.gif"></img>


### 2. SVG
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie9 이상|
|Others           |ok   |

* 벡터 그래픽을 표현하기 위한 표준 XML 마크업 랭귀지
* 이벤트 핸들러 지원
* mdn SVG     
https://developer.mozilla.org/ko/docs/Web/SVG
* SVG 가이드   
https://svgontheweb.com/ko/
* d3.js   
https://d3js.org/   
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/d3.gif"></img>


### 3. Canvas
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie9 이상|
|Others           |ok   |

* 이벤트 핸들러 지원안함(필요한경우 직접 구현하거나 라이브러리 사용해야함)
* .png나 .jpg로 이미지 저장가능
* mdn canvas      
https://developer.mozilla.org/ko/docs/Web/HTML/Canvas
* phaser (canvas game engine)   
https://phaser.io/   
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/phaser.gif"></img>

### SVG vs Canvas
https://smus.com/canvas-vs-svg-performance/   
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/varying-number-of-objects.png"></img>     
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/varying-drawing-area-height.png"></img>     

* 드로윙할 오브젝트가 증가할 수록 SVG는 canvas에 비해 가파르게 렌더링 시간이 증가한다
* 드로윙 영역이 커질 수록 canvas는 SVG에 비해 가파르게 렌더링 시간이 증가한다
* SVG는 드로윙할 오브젝트의수가 적은경우일 수록 좋다
* 수천개의 오브젝트를 조작하려면 canvas가 좋다


## 3D

### 1. CSS 3D Transforms
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie10 이상 부분지원|
|Others           |ok   |
* mdn css transform   
https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Transforms/Using_CSS_transforms
* css-tricks demo   
https://css-tricks.com/how-i-live-coded-my-most-hearted-codepen-demo/   
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/tudor-1.gif"></img>   




### 2. WebGL
|Desktop Browser  |note    |
|-----------------|--------|
|Internet Explorer|ie11 이상|
|Others           |ok      |

* OpenGL ES 2.0 기반
* mdn WebGL   
https://developer.mozilla.org/ko/docs/Web/API/WebGL_API
* three.js   
https://threejs.org/
* tdl.js   
http://greggman.github.io/tdl/example/example.html   
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/tdl.gif"></img>


## 그외
### WebAssembly
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|지원안함 |
|Others           |ok    |

https://webassembly.org/demo/   
https://developer.mozilla.org/ko/docs/WebAssembly   
https://medium.com/samsung-internet-dev/performance-testing-web-assembly-vs-javascript-e07506fd5875   
https://d2jta7o2zej4pf.cloudfront.net/   
