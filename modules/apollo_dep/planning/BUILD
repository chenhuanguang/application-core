load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_planning",
    hdrs = ["include_option.h"],
    deps = [
        "//modules/planning/planning_base:apollo_planning_planning_base",
        "//modules/planning/planning_component:planning_component_lib",
    ],
)

apollo_package()
