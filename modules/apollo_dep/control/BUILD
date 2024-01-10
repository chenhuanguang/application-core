load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_control",
    hdrs = ["include_option.h"],
    deps = [
        "//modules/control/control_component:control_component_lib",
        "//modules/control/control_component/controller_task_base/common:controllers_control_task_base_common",
    ],
)

apollo_package()
