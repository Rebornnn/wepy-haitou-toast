## wepy 海投toast组件

### 使用
- 显示toast提示： 
    - title:    提示的内容 必填
    - icon:     图标，type = success/success_no_circle/info/warn/waiting/cancel/download/search/clear
    - duration: 提示的延迟时间，单位毫秒，默认：1500, 10000永远存在除非手动清除 选填
    - mask:     是否显示透明蒙层，防止触摸穿透，默认：true 选填
    - cb:       接口调用成功的回调函数 选填