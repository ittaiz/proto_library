# Conventions:
# 1. One proto_library rule per .proto file.
# 2. A file named foo.proto will be in a rule named foo_proto.
proto_library(
    name = "all",
    srcs = glob(["*.proto"]),
    proto_source_root = package_name(),
    visibility = ["//visibility:public"],
)
