1. add gopath to gen the proto. export PATH="$PATH:$(go env GOPATH)/bin" // go env GOPATH on my mac is /users/UserName/go
2. go run server/main.go
3. go run client/main.go
4. write more rpcs in proto, gen, implementa in server...