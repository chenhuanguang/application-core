load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_external_command",
    hdrs = ["include_option.h"],
    deps = [
        "//modules/external_command/process_component:external_command_process_component_lib",
    ],
)

apollo_package()
