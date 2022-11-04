# 目的

- 下記技術を使い、スキーマ駆動開発を理解する。
  - Go
  - gRPC

# gRPC 生成コマンド

```
protoc --go_out=../gen/grpc --go_opt=paths=source_relative \
        --go-grpc_out=../gen/grpc --go-grpc_opt=paths=source_relative \
        hello.proto
```
