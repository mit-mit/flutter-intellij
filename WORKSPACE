
new_http_archive(
  url = "https://download.jetbrains.com/idea/ideaIC-2016.2.tar.gz",
  name = "intellij_ce_stable",
  sha256 = "6270c2feae18e10a790d7dda0ab5fed929e353ef41cb016560f7878101259d98",
  build_file_content = """
java_import(
  name = "libs",
  jars = glob(["idea-IC-*/lib/*.jar"]),
  visibility = ["//visibility:public"],
)
""",
)
