# GLC_Docker-compose_plus_Dockerfiles
 奇異鳥好心肝報告系統 前後端dockerfiles 加上Mongo-Replica 透過docker-compose.yaml 快速建置整套報告系統

<img src="https://github.com/johnny990628/GHL_Frontend/blob/master/public/logo.png" width="50%" />

## 整合的專案列表
### 奇異鳥好心肝報告系統-前端
+ https://github.com/johnny990628/GHL_Frontend

### 奇異鳥好心肝報告系統-後端
+ https://github.com/johnny990628/GHL_Backend

### 奇異鳥好心肝報告系統-websocket
+ https://github.com/johnny990628/websocket_mongodb

## TODO List
- [ ] Write docker-compose file
- [ ] Test docker-compose file

## 使用Docker的注意事項
+ 如果你已經在Local端成功架設前後端並且順利登入，請記得要登出後再執行前後端的Docker Container，否則你的前端會無法順利運作

## Authors 🎉
+ 李柏勳[johnny990628](https://github.com/johnny990628)
+ 楊嘉翔[Yang-Jiaxiang](https://github.com/Yang-Jiaxiang)
+ 楊曜承[luckypig3400](https://github.com/luckypig3400)

## References
+ [Docker Port Mapping](https://www.baeldung.com/linux/assign-port-docker-container#:~:text=Port%20mapping%20is%20used%20to,redirected%20into%20the%20Docker%20container.)
+ [Docker node container exited](https://stackoverflow.com/questions/44288504/why-is-my-docker-node-container-exiting)
+ [Docker Run with command](https://docs.docker.com/engine/reference/commandline/run/)
+ [Install specific NodeJS version in Ubuntu](https://www.educative.io/answers/how-to-install-nodejs-on-ubuntu)
+ [Day5: 實作撰寫第一個 Dockerfile](https://ithelp.ithome.com.tw/articles/10191016)
+ [Docker Packaging your software](https://docs.docker.com/build/building/packaging/)
+ [解決Dockerfile RUN npm install找不到package.json](https://ithelp.ithome.com.tw/articles/10204227)
+ [Node bcrypt套件在Linux上Error](https://stackoverflow.com/questions/15809611/bcrypt-invalid-elf-header-when-running-node-app)
+ [在Docker內無需使用pm2](https://stackoverflow.com/questions/51191378/what-is-the-point-of-using-pm2-and-docker-together)
+ [Run MongoDB as background service in Linux](https://serverfault.com/questions/157705/how-can-i-run-mongod-in-the-background-on-unix-mac-osx)
+ [Dockerfile CMD multiple commands](https://stackoverflow.com/questions/46797348/docker-cmd-exec-form-for-multiple-command-execution)
+ [Push image to Docker Hub](https://docs.docker.com/engine/reference/commandline/push/)
+ [MongoDB insert data](https://www.mongodb.com/docs/manual/reference/method/db.collection.insert/)
+ [透過mongosh cli直接新增資料到MongoDB](https://stackoverflow.com/questions/4837673/how-to-execute-mongo-commands-through-shell-scripts)