package(default_visibility = ["//visibility:public"])

genrule(
    name = "validator-extensions-protoascii_",
    srcs = glob(
        [
            "*/validator-*.protoascii",
        ],
    ),
    outs = ["validator-extensions-protoascii"],
    cmd = "cat $(SRCS) > $(OUTS)",
)
