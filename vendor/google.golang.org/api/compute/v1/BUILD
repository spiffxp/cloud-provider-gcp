load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["compute-gen.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/api/compute/v1",
    importpath = "google.golang.org/api/compute/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/api/googleapi:go_default_library",
        "//vendor/google.golang.org/api/internal/gensupport:go_default_library",
        "//vendor/google.golang.org/api/option:go_default_library",
        "//vendor/google.golang.org/api/option/internaloption:go_default_library",
        "//vendor/google.golang.org/api/transport/http:go_default_library",
    ],
)
