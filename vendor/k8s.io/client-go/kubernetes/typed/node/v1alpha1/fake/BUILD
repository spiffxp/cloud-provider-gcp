load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "fake_node_client.go",
        "fake_runtimeclass.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/node/v1alpha1/fake",
    importpath = "k8s.io/client-go/kubernetes/typed/node/v1alpha1/fake",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/node/v1alpha1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/labels:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/types:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/watch:go_default_library",
        "//vendor/k8s.io/client-go/applyconfigurations/node/v1alpha1:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/typed/node/v1alpha1:go_default_library",
        "//vendor/k8s.io/client-go/rest:go_default_library",
        "//vendor/k8s.io/client-go/testing:go_default_library",
    ],
)
