# h5+vue模版

## 使用的技术栈

`vue全家桶` + `vue-cli3` + `axios` +  `vant` + `scss`

## 开发前必读

1. [`vue`](https://cn.vuejs.org/) 要求：最基本需要阅读教程+API

2. [`vue-cli3`](https://cli.vuejs.org/zh/) 要求：熟悉其配置

3. [`vant`](https://youzan.github.io/vant/#/zh-CN/) 要求：最基本需要知道哪些组件并且灵活使用

## 目录说明

```md
h5-ts
|  public                 // 静态文件
|
└─src
    │  App.vue            // 页面根组件
    │  main.js            // 入口文件
    ├─assets              // 静态资源目录
    │  ├─fonts            // 字体
    │  ├─images           // 图片
    │  ├─css              // 公共scss/css文件
    │  ├─js               // 脚本
    ├─components          // 组件目录
    │  ├─loading          // 全局自定义指令v-loading文件
    |  ├─AppFooter.vue    // 底部导航栏
    |  ├─AppHeader.vue    // 头部导航栏
    |  ├─MainPanel.vue    // 公共用的container操作区域
    ├─mixins              // 全局混入文件
    │  ├─routeAnimate.js  // 路由之间的动画文件
    ├─router              // 路由文件
    ├─services            // 统一的数据请求方法
    ├─store               // vuex目录
    │
    └─utils               // 工具类
    | ├─device.js         // 设备设别
    | ├─rotateImg.js      // 图片旋转
    | ├─url.js            // 地址解析
    ├─views               // 业务页面
│  .browserslistrc        // 兼容性配置
│  .commitlintrc.js       // git提交规范
│  .editorconfig          // eslint风格配置
│  .eslintignore          // eslint忽略配置
│  .env.development       // 开发环境配置
│  .env                   // 生产环境配置
|  .eslintrc.js           // eslint配置
|  .gitignore             // git提交忽略
|  .postcssrc             // css相关配置
│  babel.config.js        // babel配置
│  jest.config.js         // 单元测试配置
│  package-lock.json      // package锁定文件
│  package.json           // package配置
│  patch.js               // ci文件
│  README.md              // readme
│  stylelint.config.js    // css检查工具配置
│  vue.config.js          // vue配置

```

## 关于注释

```js
// TODO 功能未完成，待完善
// FIXME 待修复
// XXX 实现方法待确认
// NOTE 代码功能说明
// HACK 此处写法有待优化
// BUG
```

[其他的注释详情](https://0227vera.github.io/posts/tool/%E6%B3%A8%E9%87%8A.html)

## 祝愿

```html
<!--
 *                        _oo0oo_
 *                       o8888888o
 *                       88" . "88
 *                       (| -_- |)
 *                       0\  =  /0
 *                     ___/`---'\___
 *                   .' \\|     |// '.
 *                  / \\|||  :  |||// \
 *                 / _||||| -:- |||||- \
 *                |   | \\\  - /// |   |
 *                | \_|  ''\---/''  |_/ |
 *                \  .-\__  '-'  ___/-. /
 *              ___'. .'  /--.--\  `. .'___
 *           ."" '<  `.___\_<|>_/___.' >' "".
 *          | | :  `- \`.;`\ _ /`;.`/ - ` : | |
 *          \  \ `_.   \_ __\ /__ _/   .-` /  /
 *      =====`-.____`.___ \_____/___.-`___.-'=====
 *                        `=---='
 * 
 * 
 *      ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 * 
 *            佛祖保佑       永不宕机     永无BUG
 -->
```
