scala_library(
    sources = globs("*.scala"),
    compiler_option_sets = {"fatal_warnings"},
    provides = scala_artifact(
        org = "com.twitter",
        name = "scrooge-linter",
        repo = artifactory,
    ),
    dependencies = [
        "3rdparty/jvm/com/github/scopt",
        "3rdparty/jvm/org/scala-lang/modules:scala-parser-combinators",
        "scrooge/scrooge-generator",
    ],
    exports = [
        "3rdparty/jvm/com/github/scopt",
    ],
)
