load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "conversion.go",
        "defaults.go",
        "doc.go",
        "register.go",
        "types.go",
        "zz_generated.conversion.go",
        "zz_generated.deepcopy.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/cloud-provider/controllers/service/config/v1alpha1",
    importpath = "k8s.io/cloud-provider/controllers/service/config/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/conversion:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/cloud-provider/controllers/service/config:go_default_library",
    ],
)
