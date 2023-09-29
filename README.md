# proto
电商项目rpc proto
protoc -I . --go_out=plugins=grpc:. ./user/user.proto
