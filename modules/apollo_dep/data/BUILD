load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_data",
    hdrs = ["include_option.h"],
    deps = [
        "//modules/data/proto:static_info_cc_proto",
    ],
)

apollo_package()
