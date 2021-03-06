### 互动白板小程序的两种方式
- webrtc-room + webview 
- webrtc-room + canvas

> 受限于小程序的技术方案，webrtc-room + canvas方式能力欠缺，目前主推webrtc-room + webview方式

两种方式能力对比：
|      白板功能点         |     【webrtcroom + canvas方式】支持  | 【webrtcroom + webview方式】支持 | 说明 |
| ------------------ | -------- |------|------|
| 画笔 | ✔ |  ✔ | |
| 橡皮 | ✔ |  ✔ | |
| 激光笔 | ✔  | ✔ | |
| 直线 | ✔ |  ✔ | | |
| 空心椭圆 | ✔ |  ✔ | |
| 空心矩形 | ✔ |  ✔ | |
| 实心椭圆 | ✔ |  ✔ | |
| 实心矩形 | ✔ |  ✔ | |
| 背景色 | ✔ |  ✔ | |
| 背景图 | ✔ |  ✔ | |
| H5背景 | ✖ |  ✔ | |
| 点选 | ✔ |  ✔ | |
| 框选 | ✔ |  ✔ | |
| 撤销 | ✔ |  ✔ | |
| 重做 | ✔ |  ✔ | |
| 文件展示 | ✔  | ✔ | 支持PPT、PDF、WORD、EXCEL |
| 文件上传 | ✔  | ✔ | 支持PPT、PDF、WORD、EXCEL，图片 |
| 动画H5PPT | ✖  | ✔ | |
| 放大 | ✖ |  ✔ | |
| 缩小 | ✖ |  ✔ | |
| 拖动 | ✖ |  ✔ | |
| 初始化设置白板比例 | ✔  | ✔ | |
| 文字输入/展示 | ✖ | ✔  | |
| 涂鸦平滑级别 | ✔ |  ✔  | |
| 动态设置白板比例 | ✖ |  ✔ | |
| 白板内容填充方式 | ✖ |  ✔ | |


### 目录说明

| 目录 | 说明  |
| -------- | ------ | -------------- |
| webrtc-room + canvas| webrtc-room + canvas的方式源码 | |
| webrtc-room + webview  | webrtc-room + webview的方式源码 | |
| - 小程序源码 | 小程序源码 | |
| - webview链接页面源码 | webview链接页面源码 | |