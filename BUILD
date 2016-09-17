
# TODO: forms processing
# TODO: tests

java_import(
  name = "dart-plugin",
  jars = [
    "lib/dart-plugin/lib/Dart.jar",
  ],
)

java_library(
  name = "flutter-plugin",
  deps = [":dart-plugin", "@intellij_ce_stable//:libs"],
  srcs = glob(["src/**/*.java", "gen/**/*.java", "third_party/intellij-plugins-dart/src/**/*.java"]),
  resources = glob([
    "src/main/resources/**/*.png", 
    "src/main/resources/**/*.xml",
    "src/main/java/**/*.properties",
  ]),
  javacopts = ["-g"],
)
