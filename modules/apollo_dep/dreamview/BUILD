load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_dreamview",
    hdrs = ["include_option.h"],
    deps = [
        "//modules/dreamview/backend:apollo_dreamview_backend",
    ],
)

apollo_package()
