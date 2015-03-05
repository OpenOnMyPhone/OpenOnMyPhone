# OpenOnMyPhone

## 目标
> 实现推送当前网址到手机
> 类似[Google Chrome to Phone Extension](chrome2phone)

## 工程
* Control Server
  > * 生成标示用户的Token
  > * 转发网址到推送服务
* Chrome Extension
  > * 绑定Token
  > * 推送网址至控制服务器
* iOS/Android Client
  > * 绑定Token
  > * 接受推送到的网址并使用默认浏览器打开

[chrome2phone]:https://chrome.google.com/webstore/detail/google-chrome-to-phone-ex/oadboiipflhobonjjffjbfekfjcgkhco
