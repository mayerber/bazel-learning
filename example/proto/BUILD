load("@rules_proto_grpc//cpp:defs.bzl", "cpp_proto_library")
load("@rules_proto_grpc//csharp:defs.bzl", "csharp_proto_library")

proto_library(
    name = "thing_proto",
    srcs = ["thing.proto"],
    deps = ["@com_google_protobuf//:any_proto"],
)

cpp_proto_library(
    name = "cpp_thing_proto",
    protos = [":thing_proto"],
)

csharp_proto_library(
    name = "thing_csharp_proto.dll",
    protos = [":thing_proto"],
)
