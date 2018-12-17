load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "io_bazel_rules_go",
    url = "https://github.com/bazelbuild/rules_go/archive/72f8042309ac460c7bb0c1d12e550b10a60a7e23.zip",
    strip_prefix = "rules_go-72f8042309ac460c7bb0c1d12e550b10a60a7e23",
    # sha256 = "d02b1d8d11fb67fb1e451645256e58a1542170eedd6e2ba160c8540c96f659da",
)
# local_repository(
#     name = "io_bazel_rules_go",
#     path = "../rules_go"
# )
load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")
go_rules_dependencies()
go_register_toolchains()