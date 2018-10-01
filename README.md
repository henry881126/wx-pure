# imooc-pure

> 纯正商业级应用-微信小程序开发实战 appkey

- RdshydjBvcYZhMZC
- GgRhTjUNUYn1fHke

## 5-1, 5-2, 5-3 定义引用与使用组件

- **classic.json**
- **classic.wxml**

## 5-6 小程序尺寸单位与设计原则

- iPhone6: dpi = 2, w:h = 750 X 1334 设计稿
- iPhone6: vscode 编辑器 5px = wechat 模拟器 10px
- iPhone6: rpx 比例 1:1, 不需要换算, rpx 会自适应，字体可能会用到 px, flex 解决布局, rpx 解决响应式

## 5-7, 5-8, 5-9, 5-10 苹方字体设置

- **app.wxss** ios,mac 上启用
- page 会包裹组件
- [page](https://developers.weixin.qq.com/miniprogram/dev/framework/custom-component/wxml-wxss.html)
- 继承样式(font, color), 会从组件外继承到组件内

## 5-11, 5-12 组件最好不要留有空白间距

- **like/index.wxss**

```css
/* 取消字体上下间距 */
line-height: 24rpx;
font-size: 24rpx;
/* 取消字体上下间距 */
```

## 5-13 组件事件与事件处理

- **like/index.wxml**
- `bind:tap="onLike"`
- `catch`(阻止冒泡)
- 冒泡事件：当一个组件上的事件被触发后，该事件会向父节点传递
- 非冒泡事件：当一个组件上的事件被触发后，该事件不会向父节点传递
- [事件](https://developers.weixin.qq.com/miniprogram/dev/framework/view/wxml/event.html)

## 6-1, 6-2, 6-3 三元表达式与图片切换

- **like/index.js**
- **like/index.wxml**

## 6-4, 6-5, 6-6 组件的封闭性，开放性及粒度, properties属性详解, this

- **like/index.js**
- [properties](https://developers.weixin.qq.com/miniprogram/dev/framework/custom-component/component.html)

## 7-1, 7-2 API

- 看待组件的两种观点
- Blink API介绍与测试API
- [API](https://github.com/fujiale33/old-land-flask-api/blob/master/README.md#HTTP%E7%8A%B6%E6%80%81%E7%A0%81)

## 7-3 生命周期函数

- [生命周期函数](https://developers.weixin.qq.com/miniprogram/dev/framework/app-service/page.html#%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F)

## 7-4 wx.request-4xx状态码并不会执行fail

- [wx.request](https://developers.weixin.qq.com/miniprogram/dev/api/network/request/wx.request.html)

## 7-5, 7-6, 7-7, 7-8, 7-9 访问API获取数据, 同步，异步与回调函数, ES6箭头函数与this指代

- **classic.js**
- detail -> 不校验合法域名(开发阶段)
- 500 是服务器原因, 服务端才能改
- **config.js**

## 7-10, 7-11, 7-12, 7-13 ES6 Module export 与 import, HTTP类的封装与ES6 startsWith

- **util/http.js**

## 7-15 通用错误异常处理

- **util/http.js**
- [wx.showToast](https://developers.weixin.qq.com/miniprogram/dev/api/ui/interaction/wx.showToast.html)

## 8-1, 8-2, 8-3 ‘剥夺函数return的能力’, 组件属性赋值与页面渲染流程解析, setData

- **models/classic.js**

## 8-4, 8-5 movie 组件的实现

- behavior

## 8-6 自定义事件的激活与监听

- **like/index.js** 自定义事件定义
- **classic.wxml** 自定义事件监听
- triggerEvent

## 8-7 喜欢还是不喜欢

- **models/like.jsm**
- **pages/classic.js**
- **util/http.js**

## 8-8, 8-9, 8-10, 8-11, 8-12, 8-13, 8-14

- **components/epsoide/index.js**
- 8-13: observer 函数的应用

## 9-1, 9-2, 9-3 navi 组件与移动端触碰区域讨论

- **components/navi/index.js**
- wechat 需要 https, 开发阶段可以用 http

## 9-4, 9-5, 9-6 初识组件的 behavior 行为

- **classic-beh.js**
- 子类覆盖父类属性, 生命周期不会覆盖

## 9-7 9-8, 9-10 是否是最新期刊的逻辑判断初步实现期刊切换, 函数重构

- **models/classic.js**
- 缓存处理
- wechat 清缓存

## 10-1 缓存

## 10-2 收藏

## 10-3 es6 改写 classic

## 10-4 wxss 复用

- bug

## 10-5 音乐播放控件

- **musicm** 音乐播放控件

## 11-1 底部栏

## 11-2 promise

## 11-3 http.js -> http-p.js

## 11-4 promise callback

## 12-1 book style

## 12-2 cycle

- cycle `wx:for` use `<block></block>`

## 12-3 book.wxml

## 12-4 slot
