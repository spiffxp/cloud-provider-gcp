load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["webhook.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/plugin/pkg/authenticator/token/webhook",
    importpath = "k8s.io/apiserver/plugin/pkg/authenticator/token/webhook",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/authentication/v1:go_default_library",
        "//vendor/k8s.io/api/authentication/v1beta1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/net:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/authentication/authenticator:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/authentication/user:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/webhook:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/scheme:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/typed/authentication/v1:go_default_library",
        "//vendor/k8s.io/klog/v2:go_default_library",
    ],
)
