cc_library(
  name = "greet",
  srcs = ["src/greet.cc"],
  hdrs = ["src/greet.h"],
  visibility = ["//src:__pkg__"]
)

cc_binary(
  name = "main",
  srcs = [
    "src/main.cc",
    "src/greet.h"
  ],
  deps = [
    ":greet"
  ]
)