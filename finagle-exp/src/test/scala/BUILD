junit_tests(
    sources = ["**/*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    dependencies = [
        "3rdparty/jvm/com/netflix/concurrency:concurrency-limits-core",
        "3rdparty/jvm/junit",
        "3rdparty/jvm/org/mockito:mockito-all",
        "3rdparty/jvm/org/scalatest",
        "3rdparty/jvm/org/scalatestplus:junit",
        "3rdparty/jvm/org/scalatestplus:mockito-1-10",
        "finagle/finagle-core/src/main",
        "finagle/finagle-core/src/test/scala:stringprotocol",
        "finagle/finagle-exp",
        "finagle/finagle-thrift/src/main/java",
        "util/util-core:scala",
        "util/util-stats",
    ],
)
