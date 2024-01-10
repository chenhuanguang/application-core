load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_dep_routing",
    hdrs = ["include_option.h"],
    deps = [
        "//modules/routing:routing_component_lib",
    ],
)

apollo_package()
