# 目的

- 下記技術を使い、スキーマ駆動開発を理解する。
  - Go
  - gRPC

# gRPC 実行コマンド

```
grpcurl -plaintext -d '{"name": "hsaki"}' localhost:8080 myapp.GreetingService.Hello
```
