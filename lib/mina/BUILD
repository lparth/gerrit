java_library(
    name = "sshd",
    data = ["//lib:LICENSE-Apache2.0"],
    visibility = ["//visibility:public"],
    exports = [
        ":eddsa",
        "@sshd//jar",
    ],
    runtime_deps = [":core"],
)

java_library(
    name = "eddsa",
    data = ["//lib:LICENSE-CC0-1.0"],
    visibility = ["//visibility:public"],
    exports = [
        "@eddsa//jar",
    ],
)

java_library(
    name = "core",
    data = ["//lib:LICENSE-Apache2.0"],
    visibility = ["//visibility:public"],
    exports = ["@mina_core//jar"],
)
