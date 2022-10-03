load("@io_bazel_rules_scala//scala:scala.bzl", "scala_binary", "scala_library", "scala_test")

package(default_visibility = ["//visibility:public"])

scala_library(
    name = "demo",
    srcs = glob(["*.scala"]),
    scalacopts = [
        "-Xsource:3",
    ],
    exports = [],
    deps = [],
)

scala_binary(
    name = "app",
    srcs = glob(["*.scala"]),
    main_class = "demo.Demo",
    scalacopts = [
        "-Xsource:3",
    ],
)
