scala_library(
    name = "integration-client",
    sources = [
        "com/twitter/finagle/mysql/integration/IntegrationClient.scala",
    ],
    compiler_option_sets = ["fatal_warnings"],
    dependencies = [
        "3rdparty/jvm/org/scalatest",
        "finagle/finagle-mysql/src/main/scala",
    ],
)

junit_tests(
    sources = ["**/*.scala"],
    compiler_option_sets = ["fatal_warnings"],
    dependencies = [
        "3rdparty/jvm/com/github/ben-manes/caffeine",
        "3rdparty/jvm/junit",
        "3rdparty/jvm/mysql:mysql-connector-java",
        "3rdparty/jvm/mysql:mysql-connector-mxj-gpl-db-files",
        "3rdparty/jvm/org/mockito:mockito-all",
        "3rdparty/jvm/org/scalatest",
        "3rdparty/jvm/org/scalatestplus:junit",
        "3rdparty/jvm/org/scalatestplus:mockito-1-10",
        "finagle/finagle-core/src/main",
        "finagle/finagle-mysql",
        "finagle/finagle-mysql/src/test/resources",
        "util/util-core:scala",
    ],
)
