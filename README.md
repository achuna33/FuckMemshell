# FuckMemshell
内存马持久化

通过ASM 改写 tomcat-websocket.jar WsFilter

目前还没想好怎么工具化（后续如果有好的想法可能会继续写这个工具，没有得话就搁浅一下了）

先丢出一个可利用的jar，替换原有jar包即可
目标重启服务后内存马重新加载。

![image](https://user-images.githubusercontent.com/48993128/169270136-932d46b8-ad53-4c2f-80f5-513a6327e041.png)

