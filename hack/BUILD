package(default_visibility = ["//visibility:public"])


# this does not work, and I am uncertain we will need it
#sh_test(
#    name = "verify-packages",
#    srcs = ["verify-packages.sh"],
#    tags = ["manual"],
#)

sh_test(
    name = "verify-boilerplate",
    srcs = ["verify-boilerplate.sh"],
    tags = ["manual"],
)

sh_test(
    name = "verify-gofmt",
    srcs = ["verify-gofmt.sh"],
    tags = ["manual"],
)

test_suite(
    name = "verify-all",
    tags = ["manual"],
    tests = [
        "verify-boilerplate",
        #"verify-packages",
        "verify-gofmt",
    ],
)

