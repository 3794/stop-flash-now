# Stop Flash Now
## 플래시를 없애자!

Adobe는 2020년 말에 Flash Player를 업데이트 하고 배포하는것을 중단하기로 하였습니다. 크롬은 2020년 12월에 플래시를 크롬에서 제거하기로 하였습니다. 그래서 그전에 기존 플래시 모듈은 전부 제거 되어야 합니다. 2020년 까지 관련 뉴스를 정리하고, 플래시를 대체하는 기술들에 대해 소개하도록 하겠습니다.

## 2D

### 1. CSS 2D Transforms
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie9 이상|
|Others           |ok   |

* mdn css transform   
https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Transforms/Using_CSS_transforms

### 2. SVG
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie9 이상|
|Others           |ok   |

* mdn SVG     
https://developer.mozilla.org/ko/docs/Web/SVG
* d3.js   
https://d3js.org/

### 3. Canvas
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie9 이상|
|Others           |ok   |

* mdn canvas      
https://developer.mozilla.org/ko/docs/Web/HTML/Canvas
* phaser (canvas game engine)   
https://phaser.io/

## 3D

### 1. CSS 3D Transforms
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie10 이상 부분지원|
|Others           |ok   |
* mdn css transform 문서   
https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Transforms/Using_CSS_transforms

### 2. WebGL
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|ie11 이상|
|Others           |ok   |
* mdn WebGL   
https://developer.mozilla.org/ko/docs/Web/API/WebGL_API


## 퍼포먼스
### 1. WebAssembly
|Desktop Browser  |note   |
|-----------------|-------|
|Internet Explorer|지원안함|
|Others           |ok   |
* mdn WebAssembly   
https://developer.mozilla.org/ko/docs/WebAssembly   
> 간단히 말해서 여러 언어로 작성된 코드들을 네이티브에 가까운 속도로 웹에서 돌릴 수 있는 길을 제공하며, 이전까지는 웹에서 돌려볼 수 없었던 클라이언트 앱들을 웹에서 돌릴 수 있도록 만들어주기 때문입니다.

## News
* Adobe flash 지원 중단   
https://theblog.adobe.com/adobe-flash-update/
> 특히 2020 년 말에 Flash Player를 업데이트하고 배포하는 것을 중단하고 기존의 Flash는 오픈 웹 포멧으로 마이그레이션하도록 권장 할 것입니다.

* Chrome Flash 제거 계획   
https://www.blog.google/products/chrome/saying-goodbye-flash-chrome/

* Chromium 플래시 로드멥   
https://www.chromium.org/flash-roadmap

* Microsoft Edge, IE Flash 제거 계획   
https://blogs.windows.com/msedgedev/2017/07/25/flash-on-windows-timeline/

* Microsoft IE 10 이하 지원 중단   
https://www.microsoft.com/ko-kr/windowsforbusiness/end-of-ie-support

* 7월쯤 배포될 예정인 Chrome 76 부터는 경고문구 계속 노출   
https://9to5google.com/2019/03/22/chrome-warn-flash-player-deprecation-july/
<img src="https://github.com/3794/stop-flash-now/blob/master/assets/chrome-flash-deprecation-warning.png"></img>


