# 3d个人网站
原作者  [https://github.com/0xFloyd/Portfolio_2020](https://github.com/0xFloyd/Portfolio_2020)

另外参考了一个up的汉化版，但是时间长了找不到了，知道谁的话踢我一下，我标注上
最终效果：[alleniverrui.top](alleniverrui.top)

## 项目运行

```
// 安装依赖
npm install & cnpm install

// 本地运行
npm run dev

// 打包
npm run build
```

## 更改

```js
// texture.js

let billboardTextures = {};
// 第一块展板图片地址
billboardTextures.blogTexture = '../src/jsm/blog.png';
// 第二块展板图片地址
billboardTextures.musicTexture =
  '../src/jsm/music.png';
// 第三块展板图片地址
billboardTextures.fundTexture =
  '../src/jsm/fund.png';

let boxTexture = {};
// 链接的图标地址
boxTexture.Github = '../src/jsm/githubLogo.png';
boxTexture.BiliBili = '../src/jsm/BiliBili.png';
boxTexture.QQ = '../src/jsm/qq.png';
boxTexture.mail = '../src/jsm/envelope.png';
boxTexture.reactIcon = '../src/jsm/react.png';
boxTexture.allSkills = '../src/jsm/allSkills.png';
boxTexture.lensFlareMain = '../src/jsm/lensflare0.png';
boxTexture.skrillex = '../src/jsm/lzw2.jpg';
boxTexture.edmText = '../src/jsm/EDM.png';

// 砖块材质
let stoneTexture = '../src/jsm/stone.png';
// 展板木头材质
let woodTexture = '../src/jsm/woodTexture.jpg';

// 文字图片地址
let inputText = {};
inputText.terpSolutionsText = '../src/jsm/terp-solutions-text.png';
inputText.activities = '../src/jsm/activities_text.png';
inputText.bagholderBetsText = '../src/jsm/bagholderbets-text.png';
inputText.homeSweetHomeText = '../src/jsm/home-sweet-home-text.png';
inputText.staticPortfolio = '../src/jsm/static-portfolio.png';
inputText.pcControl = '../src/jsm/pc-control.png'
inputText.mobileControl = '../src/jsm/mobile-control.png'
inputText.link = '../src/jsm/link.png'

//SVG
let SVG = {};
SVG.reactLogo = '../src/jsm/react-svg.svg';
