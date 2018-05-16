# Chat Example

这个demo参考了[websocket](https://github.com/gorilla/websocket)里面的demo，
然后在此基本上加了session和[mux](https://github.com/gorilla/mux)，做为go语言入门的小项目。

## Running the demo
    go run *.go

open http://localhost:8080/

## Technology Stack
* [mux](https://github.com/gorilla/mux)
* [gorm](https://github.com/jinzhu/gorm)
* [securecookie](https://github.com/gorilla/securecookie)
* [websocket](https://github.com/gorilla/websocket)
## Docker
    docker build -t chat .
    docker run -p 8080:8080 chat

## TODO LIST

- [x] dockerfile
- [ ] 消息提醒
- [x] 数据存储
- [ ] 房间分隔
- [ ] 房间密码
- [ ] 在线人数