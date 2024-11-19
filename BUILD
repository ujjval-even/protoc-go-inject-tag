load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library")

go_library(
    name = "protoc_go_inject_tag_lib",
    srcs = glob(["*.go"]),
    importpath = "github.com/favadi/protoc-go-inject-tag",
    visibility = ["//visibility:private"],
)

go_binary(
    name = "protoc-go-inject-tag",
    embed = [":protoc_go_inject_tag_lib"],
    visibility = ["//visibility:public"],
)
