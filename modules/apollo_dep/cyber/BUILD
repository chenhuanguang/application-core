load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_cyber",
    hdrs = ["include_option.h"],
    deps = [
        "//cyber",
        "//cyber/proto:dag_conf_cc_proto",
        "//cyber/proto:component_conf_cc_proto",
    ],
)

apollo_package()
