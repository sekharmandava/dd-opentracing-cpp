workspace(name = "com_github_datadog_dd_opentracing_cpp")
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_opentracing_cpp",
    sha256 = "015c4187f7a6426a2b5196f0ccd982aa87f010cf61f507ae3ce5c90523f92301",
    strip_prefix = "opentracing-cpp-1.5.1",
    urls = ["https://github.com/opentracing/opentracing-cpp/archive/v1.5.1.tar.gz"],
)

http_archive(
    name = "com_github_msgpack_msgpack_c",
    sha256 = "9859d44d336f9b023a79a3026bb6a558b2ea346107ab4eadba58236048650690",
    strip_prefix = "msgpack-3.0.1",
    urls = [
        "https://github.com/msgpack/msgpack-c/releases/download/cpp-3.0.1/msgpack-3.0.1.tar.gz",
    ],
    build_file = "@//:bazel/external/msgpack.BUILD"
)
