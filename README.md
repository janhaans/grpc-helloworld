# Create grpc client and server stubs
`> make protoc`

# Start greeting server
In terminal 1:
`> go run ./server/main.go`

# Start greeting client
In terminal 2:
`> go run .client/main.go --name="Tommie"`