load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")
git_repository(
    name = "io_bazel_rules_dotnet",
    remote = "https://github.com/lb5tr/rules_dotnet",
    commit = "43479c10ef07156a29a4265caa72db33279219db"
)

load("@io_bazel_rules_dotnet//dotnet:defs.bzl", "core_register_sdk", "nuget_package", "dotnet_register_toolchains")

dotnet_register_toolchains()
core_register_sdk("v2.2.402", name = "core_sdk")
