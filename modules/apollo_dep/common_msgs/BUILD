load("//tools/proto:proto.bzl", "proto_library")
load("//tools:apollo_package.bzl", "apollo_package", "apollo_cc_library")

package(default_visibility = ["//visibility:public"])

apollo_cc_library(
    name = "apollo_common_msgs",
    hdrs = ["include_option.h"],
    deps = [
        "//modules/common_msgs/chassis_msgs:chassis_cc_proto",
        "//modules/common_msgs/chassis_msgs:chassis_detail_cc_proto",
        "//modules/common_msgs/monitor_msgs:monitor_log_cc_proto",
        "//modules/common_msgs/basic_msgs:drive_event_cc_proto",
        "//modules/common_msgs/control_msgs:control_cmd_cc_proto",
        "//modules/common_msgs/control_msgs:control_pad_msg_cc_proto",
        "//modules/common_msgs/planning_msgs:navigation_cc_proto",
        "//modules/common_msgs/monitor_msgs:system_status_cc_proto",
        "//modules/common_msgs/perception_msgs:perception_obstacle_cc_proto",
        "//modules/common_msgs/perception_msgs:traffic_light_detection_cc_proto",
        "//modules/common_msgs/planning_msgs:pad_msg_cc_proto",
        "//modules/common_msgs/planning_msgs:planning_cc_proto",
        "//modules/common_msgs/prediction_msgs:prediction_obstacle_cc_proto",
        "//modules/common_msgs/routing_msgs:routing_cc_proto",
        "//modules/common_msgs/external_command_msgs:lane_follow_command_cc_proto",
        "//modules/common_msgs/external_command_msgs:command_status_cc_proto",
        "//modules/common_msgs/external_command_msgs:valet_parking_command_cc_proto",
        "//modules/common_msgs/planning_msgs:planning_command_cc_proto",
        "//modules/common_msgs/storytelling_msgs:story_cc_proto",
        "//modules/common_msgs/transform_msgs:transform_cc_proto",
        "//modules/common_msgs/sensor_msgs:pointcloud_cc_proto",
        "//modules/common_msgs/sensor_msgs:sensor_image_cc_proto",
        "//modules/common_msgs/guardian_msgs:guardian_cc_proto",
        "//modules/common_msgs/localization_msgs:gps_cc_proto",
        "//modules/common_msgs/localization_msgs:imu_cc_proto",
        "//modules/common_msgs/map_msgs:map_cc_proto",
        "//modules/common_msgs/localization_msgs:localization_cc_proto",
        "//modules/common_msgs/simulation_msgs:grading_condition_cc_proto",
        "//modules/common_msgs/basic_msgs:geometry_cc_proto",
        "//modules/common_msgs/prediction_msgs:scenario_cc_proto",
        "//modules/common_msgs/dreamview_msgs:hmi_config_cc_proto",
    ],
)

# proto_library(
#     name = "apollo_common_msgs_proto",
#     deps = [
#         "//modules/common_msgs/planning_msgs:planning_proto",
#         "//modules/common_msgs/routing_msgs:routing_proto",
#         "//modules/common_msgs/basic_msgs:header_proto",
#         "//modules/common_msgs/perception_msgs:traffic_light_detection_proto",
#         "//modules/common_msgs/planning_msgs:pad_msg_proto",
#         "//modules/common_msgs/map_msgs:map_geometry_proto",
#     ],
# )

apollo_package()
