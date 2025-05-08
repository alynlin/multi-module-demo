```
mkdir multi-module-demo
cd multi-module-demo/
mkdir core api storge
go mod init github.com/alynlin/multi-module-demo/core
go mod init github.com/alynlin/multi-module-demo/api
go mod init github.com/alynlin/multi-module-demo/storage

 go work init core api storage
```
