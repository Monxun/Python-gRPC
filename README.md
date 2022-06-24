# Python-gRPC
Python gRPC microservice repo

https://www.vinayshetty.dev/protobuf-cheat-sheet/
https://github.com/codethecoffee/proto-cheatsheet
https://gist.github.com/shankarshastri/c1b4d920188da78a0dbc9fc707e82996

https://itnext.io/a-minimalist-guide-to-protobuf-1f24fbca0e2d
https://manish-tiwari.medium.com/grpc-protobuf-data-types-7148ce60b54b


What's gRPC?

- Microservice 
- gRPC solves all of the issues 
- free and open source 

What's rpc?
remote procedure call

//////////////////////////////////////////////////
Client Code:

{code}
...
server.CreateUser(user)
...
{code}

//////////////////////////////////////////////////
Server Code:

// function creating users
def CreateUser(User, user) {
    ...
}


//////////////////////////////////////////////////

HOW?!

1. Define messages and services using "Protocol Buffers"
2. Rest of the gRPC code will be generated automatically and you'll have to provide an iplimentation of it
3. One .proto file works for over 12 programming languages (server and client), and allows you to use a framework that scales to millions of RPC per second
4. 

Katana-Orchestrator

BUILD TDengine + Grafana + Dapr
