Code sample for gRPD from: 

https://grpc.io/docs/languages/python/quickstart/

https://github.com/grpc/grpc/tree/master/examples

Regenerate the protobuf _pb2 files using:

> python -m grpc_tools.protoc -I. --grpc_python_out=. helloworld.proto
