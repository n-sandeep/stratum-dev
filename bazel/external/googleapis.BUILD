load(
    "@com_github_stratum_stratum//bazel/rules:proto_rule.bzl",
    "stratum_cc_proto_library",
)

package(
    default_visibility = [ "//visibility:public" ],
)

stratum_cc_proto_library(
    name = "status_cc_proto",
    srcs = ["google/rpc/status.proto"],
    with_grpc = False,
    include_wkt = True,
)

stratum_cc_proto_library(
    name = "code_cc_proto",
    srcs = ["google/rpc/code.proto"],
    with_grpc = False,
    include_wkt = True,
)