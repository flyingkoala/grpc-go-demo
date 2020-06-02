# grpc-go-demo
说明：一个Golang语言集成gRpc的helloworld的demo   
包括客户端 服务端 以及proto文件   
并支持springboot客户端调用

## proto文件编译为go文件命令
// protoc --go_out=plugins=grpc:{输出目录}  {proto文件}   
protoc --go_out=plugins=grpc:./helloworld/ ./helloworld.proto


