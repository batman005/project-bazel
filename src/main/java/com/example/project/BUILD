java_library(
    name = "util_lib",
    srcs = glob(["utils/*.java"]),
    visibility = ["//visibility:public"],
)
java_binary(
    srcs = ["HelloWorld.java"],
    main_class = "main.java.com.example.project.HelloWorld",
    name = "hello_world",
    deps = [
        ":util_lib"
    ],
)

# home work 
# What is diff between deps and runtime deps
# How the path mechanism is working