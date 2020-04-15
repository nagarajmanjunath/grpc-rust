# grpc-rust





protoc --rust_out=./proto/src/ --grpc_out=./proto/src/ --plugin=protoc-gen-grpc=`which grpc_rust_plugin` ./proto/helloworld.proto