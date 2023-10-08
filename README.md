# GRPC-Gateway HelloWorld

## Resoures
- https://github.com/grpc-ecosystem/grpc-gateway
- https://github.com/iamrajiv/helloworld-grpc-gateway/tree/main

## Usage

Install Buf via npm
```bash
npm install -g @bufbuild/buf
```

Build    
```bash
npx buf generate
```

Run Server
```bash
$ go run main.go
```

Test Http
```bash
curl -X POST -k http://localhost:8090/v1/example/echo -d '{"name": " hello"}'
```