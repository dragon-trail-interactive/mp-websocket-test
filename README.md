# mp-websocket-test

> 检测小程序进入后台后多久 websocket 会断开

## 使用方法

安装依赖, 部署到服务器, 在小程序写 WebSocket 连接上, 看着连接上后让小程序进入后台, 看多久会断开. 

## 结论

断开时间不能靠猜的, 只能做成小程序进入后台, 主动断开, 小程序进入前台, 主动重连, 重连后恢复现场 :)
