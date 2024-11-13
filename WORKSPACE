load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_github_google_rules_install",
    urls = ["https://github.com/google/bazel_rules_install/releases/download/0.4/bazel_rules_install-0.4.tar.gz"],
    sha256 = "ac2c9c53aa022a110273c0e510d191a4c04c6adafefa069a5eeaa16313edc9b9",
    strip_prefix = "bazel_rules_install-0.4",
)

load("@com_github_google_rules_install//:deps.bzl", "install_rules_dependencies")
install_rules_dependencies()
load("@com_github_google_rules_install//:setup.bzl", "install_rules_setup")
install_rules_setup()
