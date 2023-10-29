load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library")

go_binary(
    deps = [":message"],
    name = "hello",
    srcs = ["hello.go"],
)

go_library(
    name = "message",
    importpath = "github.com/GrayBuckley/ECSShell/message",
    srcs = ["message.go"],
)