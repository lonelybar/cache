package(default_visibility = ["//visibility:public"])

load(
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "store.go",
        "thread_safe_store.go",
        "index.go",
    ],
    importmap = "github.com/agilesoda/cache",
    importpath = "github.com/agilesoda/cache",
    deps = [
        "//k8s.io/apimachinery/pkg/api/meta:go_default_library",
        "//k8s.io/apimachinery/pkg/util/sets:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)
