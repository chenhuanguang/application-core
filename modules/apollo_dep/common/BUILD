load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_common",
    hdrs = ["include_option.h"],
    deps = [
        "//modules/common/adapters:adapter_gflags",
        "//modules/common/util:util_tool",
        "//modules/common/configs:vehicle_config_helper",
        "//modules/common/math",
        "//modules/common/status",
        "//modules/common/filters",
    ],
)

apollo_package()
