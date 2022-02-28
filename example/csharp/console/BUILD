load("@io_bazel_rules_dotnet//dotnet:defs.bzl", "csharp_binary")

csharp_binary(
    name = "console.exe",
    srcs = [
        "Program.cs",
    ],
    deps = [
        "@core_sdk_stdlib//:libraryset",
    ],
)
