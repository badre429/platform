load("//tools:defaults.bzl", "ng_module")

package(default_visibility = ["//visibility:public"])

exports_files(["package.json"])

ng_module(
    name = "testing",
    srcs = glob([
        "*.ts",
        "src/**/*.ts",
    ]),
    module_name = "@ngrx/store/testing",
    visibility = ["//visibility:public"],
    deps = [
        "//modules/store",
        "@npm//@angular/core",
        "@npm//rxjs",
    ],
)
